在域名的记录管理页有如下提示，说明 DNS 服务器不正确，需将域名 DNS 修改为提示的 DNS 地址，解析方可生效。
![1](//mc.qcloudimg.com/static/img/461b3011772da9f667c9e54dd45ef660/image.png)
>**注意：**
>不同解析套餐对应的 DNS 地址不同，请根据提示来修改。

### 腾讯云注册域名修改 DNS
如果域名在腾讯云注册，或者已转入腾讯云，可以通过以下步骤修改 DNS 服务器：
1. 登录 [腾讯云控制台](https://console.cloud.tencent.com/)，选择【云产品】>【域名注册】。
![1](https://main.qcloudimg.com/raw/a6db6f18b3144223eabddcffd34d628f.png)
2. 选择相应域名，单击【管理】。
![2](//mc.qcloudimg.com/static/img/1dbc9f9c19eb5543fcde41577e817ff0/image.png)
3. 【修改】DNS 服务器。
![3](//mc.qcloudimg.com/static/img/f4178f07026b20d51e6cf7ae7a41c07c/image.png)
4. 填写指定的 DNS 服务器地址。
![4](https://mc.qcloudimg.com/static/img/0b866d917b994eb84eab2a58b6cd16e3/5.png)

如果域名在其他注册商处管理，您需要前往域名注册商提供的域名管理页面，修改为指定的域名 DNS。
下面以阿里云（万网）、GoDaddy 为例说明修改方法。

### 阿里云（万网）注册商域名修改 DNS
1. 选择需要在腾讯云进行解析的域名，进入域名管理页的【DNS 修改/创建】，单击【修改域名 DNS】；
![](https://mccdn.qcloud.com/static/img/2ade9bc496f296f14186df348835ed8e/image.png)
2. 分别填写 f1g1ns1.dnspod.net，f1g1ns2.dnspod.net，保存后最长等待 72 小时可以全球生效。
![](https://mccdn.qcloud.com/static/img/bca1fc5a448568567c3498b3d2c0da4d/image.png)

### GoDaddy 注册商域名修改 DNS
1. 登录 [GoDaddy](http://www.godaddy.com) 后单击【DOMAINS】的【Manage】。
![1](https://mccdn.qcloud.com/static/img/857a65f25a4c950dab04f36c6773bf20/GD-1.png)
2. 在域名列表中找到要修改要修改 DNS 的域名，然后单击该域名下拉列表中的 【Set NameServers】。
![2](https://mccdn.qcloud.com/static/img/d692fab785a928ebbfc183637bdd9c31/GD-2.png)
3. 选择【Custom】，再单击左下角的【Add Nameserver】。
![3](https://mccdn.qcloud.com/static/img/2b5194f50b656d4d75666d2357f784b6/GD-3.png)
4. 分别输入 f1g1ns1.dnspod.net、f1g1ns2.dnspod.net，然后单击【Add Nameserver】，再单击【Save】，等待全球递归 DNS 服务器刷新（最多72 小时）。
![4](https://mccdn.qcloud.com/static/img/bed919b5d4fe0b33b6bc9f537dce1a8d/GD-4.png)
![5](https://mccdn.qcloud.com/static/img/8c4f15a5fa913037a06f752ac62ac22b/GD-5.png)

