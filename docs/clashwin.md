# 使用教程 —— Windows Clash
- - -

!>系统环境： Windows 10 LTSC 2019  Clash for Windows 0.5.15

**下载和安装 Clash for Windows**

新版本的 Clash for Windows 已经内置了 Clash 核心程序，因此无需手动下载 Clash 核心。

点击[这里](https://github.com/Fndroid/clash_for_windows_pkg/releases/)来下载 Clash for  Windows

执行 Clash for Windows 需要管理员权限，请确保在 UAC 授权中允许这么做。

**1. 使用桌面浏览器登录到 Boom Cloud 管理门户**

建议使用Chrome浏览器，访问 Boom Cloud 管理门户,点击您的订阅进入订阅详情页面



**2. 导入 Boom Cloud 接入点信息**

点击订阅打开订阅详情页面，然后找到「自动配置」功能区。然后点击「托管配置」按钮，


点击之后会自动复制成功，部分浏览器会弹出提示

![](/img/clashwin/00.png)



打开 Clash 客户端，选择 Profiles 选项，在空白处填入复制成功的地址 ，注意检查地址以`https://api.boomss.host/XXXXX`开头

!>此处请确认阁下的配置必须是兼容原版配置才可以正常使用 

![](/img/clashwin/01.png)  

然后点击`Update`按钮或者 `Direct mode` 按钮，一般建议使用  `Direct mode` 模式，当设置成功后如下图会显示`All set` 。	

![](/img/clashwin/02.png)

点击`Proxies`选项，选择 `Rule` 选项，在下列节点中选择要使用的节点，另外 此处 Global 即全局模式，Rule即规则模式，Direct即不走代理模式。

!>建议阁下默认使用`Rule`模式 

![](/img/clashwin/03.png)

点击 General 选项，勾选 System Proxy 。

![](/img/clashwin/04.png)

一小段时间后（具体时间取决于您的网络情况），您将会看到连接状态为已经连接，即可开启膜法网上之旅。

![](/img/clashwin/05.png)


- - -
注意事项：  
1. 个人专属配置文件是你个人账号密码及节点的总集成，不能泄露给任何人及网络，以防止他人使用及知晓你的密码。  
2. 如果节点有更新，则需要再次导入配置文件进行更新。  
3. Clash for windows如果出现BUG请联系软件作者，BoomCloud无法解决客户端层面问题。