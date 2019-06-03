# 扩展教程--Proxifier配合SSR  玩游戏

---

由于shadowsocks使用的是sockets5代理，一般情况下只有浏览器支持，可以实现科学上网。但很多用户希望自己的应用软件，像outlook或游戏之类的软件也实现科学上网。这就需要proxifier的配合。

软件可以在官网下载，[https://www.proxifier.com/](https://www.proxifier.com/)

官网无法下载的也可在如下百度网盘下载，  Windows，[点击下载](https://mdzz.press/工具集合/ProxifierSetup.exe)

目前仅支持windows和mac os，不支持手机。

此软件为收费软件，这里提供两个注册码, 软件分为**Standard Edition**和**Portable Edition**版本，注册码不通用，注册用户名任意。

```
L6Z8A-XY2J4-BTZ3P-ZZ7DF-A2Q9C（Portable Edition）
5EZ8G-C3WL5-B56YG-SCXM9-6QZAP（Standard Edition）
P427L-9Y552-5433E-8DSR3-58Z68（MAC）
```

* 打开软件，首先配置代理服务器。

![](/img/game/proxifier1.png)

* 如下图，添加地址127.0.0.1，以及shadowsocks里配置的本地端口，默认为1080，选择socks version 5

![](/img/game/proxifier2.png)

* 配置好后，点击测试，如果显示下图的绿色文字，则表示配置正确。

![](/img/game/proxifier3.png)

* 接下来就要添加规则，来确定哪些软件是走代理的，哪些不用

![](/img/game/proxifier4.png)

* 按如图所示的添加，这里有个default规则，如果default旁边的action里边选择的时proxy socks5…则本机所有软件都会走代理。一般default会选direct，然后把你需要走代理的软件选成proxy socks5

![](/img/game/proxifier8.png)

* 最后在首页就能看到你各个软件的情况。玩儿游戏的同理规则里添加你的游戏，希望你能玩儿的开心快乐

![](/img/game/proxifier6.png)

---
<center>特别提示：本教程转载自互联网，如无法成功或无效，请自寻谷歌。</center>