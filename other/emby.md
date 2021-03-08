# **如何获取BoomCloud-Emby专属影视服务**
- - - 
## **1. 如何获取专属账号？**

* BoomCloud为所有有效用户免费提供Emby影视服务，资源主要提供方:普拉斯影业 
* 用户可通过telegram bot: @BoomEmbyBot 创建个人账号。
* 具体创建方法可在私聊机器人后 输入 /register ， 即可获得专属账号密码。 

## **2. 哪些线路可以解锁BoomCloud专属Emby资源？**

下列节点可以正常访问解锁我们的Emby专属服务，当您需要观看影片时应当确认切换到以下节点上
* 美国1-12
* 日本1-10
* 新加坡1-4

## **3. Emby客户端收费破解？**
* 以下列出部分平台Emby客户端破解方法，未列出以及未尽事宜请通过Google自行解决，工单不接受任何关于Emby服务的支持以及咨询

### iOS
Surge 模块
Module: `https://subweb.oss-cn-hongkong.aliyuncs.com/Module/embyUnlocked.sgmodule`

QuanX 重写
Rewrite: `https://subweb.oss-cn-hongkong.aliyuncs.com/Module/embyUnlocked.conf`

Loon 插件
Plugin: `https://subweb.oss-cn-hongkong.aliyuncs.com/Module/embyUnlocked.plugin`

Shadowrocket 配置
Config: `https://subweb.oss-cn-hongkong.aliyuncs.com/Ruleset/Shadowrocket.conf`

```
[Script]
EmbyPremiere = type=http-response,script-path=https://subweb.oss-cn-hongkong.aliyuncs.com/Script/embyPremiere.js,pattern=^https?:\/\/mb3admin.com\/admin\/service\/registration\/validateDevice,max-size=131072,requires-body=true,timeout=10,enable=true
[MITM]
hostname = mb3admin.com
```
### Android
Android手机客户端下载
[下载地址](https://cdn.t9c.co/emby/Emby_Android_v3.1.23_Unlocked.apk)

AndroidTV盒子客户端下载
[下载地址](https://cdn.t9c.co/emby/Emby_AndroidTV_1.8.54gUnlocked.apk)

### Windows

**下载**
* Emby Theater 官方源 ：
– Windows：[GitHub](https://github.com/MediaBrowser/emby-theater-windows/releases/download/3.0.13/emby-theater-x64.zip)

PS: 顺带加快了初次打开 Emby Theater 的速度

**安装方法**
1. 删除 Emby Theater 安装目录下的`Emby-Theater\data` 目录
2. 找到 `main.js`
3. Windows:
`Emby-Theater\system\electronapp\main.js`
`emby-theater-x64\electronapp\main.js`
Linux:`/usr/lib/emby-theater/resources/app/main.js`

**修改文件**
使用编辑器（如 visual studio code）打开 `main.js`

搜索找到

```
function getAppBaseUrl() {
        var url = 'https://tv.emby.media';
        //url = 'http://localhost:8088';
        return url;
    }
```
修改为
```
function getAppBaseUrl() {
        var url = 'https://emby.mui.host:443';
        //url = 'http://localhost:8088';
        return url;
    }
```
保存即可

注意
如果你的 Emby Theater 更新了，你需要重新执行上述步骤.

### Linux
* Emby Theater 官方源 ：
– Linux-X64：[GitHub](https://github.com/MediaBrowser/emby-theater-electron/releases/download/3.0.12/emby-theater_3.0.12_amd64.deb)
– Linux-rpi：[GitHub](https://github.com/MediaBrowser/emby-theater-electron/releases/download/3.0.12/emby-theater-rpi_3.0.12.zip)

* 操作步骤参考Windows平台即可

---
**未列出以及未尽事宜请通过Google自行解决，工单不接受任何关于Emby服务的支持以及咨询**