# 使用教程 —— Quantumult

- - -

Quantumult 是新生代的 iOS 代理软件，在完整兼容 SSR 新协议的同时，也兼容 Surge 配置文件的大部分语法和高于 Shadowrocket 的稳定性，是目前在 iOS 设备上使用 BoomCloud 服务的一个较佳选择。

 **购买须知：**

>1.目前此应用程序无法在中国大陆的 App Store 购买和下载，请阁下自备美区App Store帐号 ，购买此软件应用程序。  
2.此外，我司不提供任何共享账号，建议阁下通过其他渠道购买帐号或者自行注册。

**注意事项：**  

!> Quantumult 于 2017年12月02日 正式添加到 BoomCloud的主流支持中，BoomCloud将提供关于此应用程序的配置和使用支持服务。然而，由于此应用程序并非 BoomCloud开发，我们的支持人员培训程度也并不相同，我们建议如果用户使用过程中出现应用程序方面的问题，优先考虑询问开发者。

---

** 1. 使用浏览器登录到 BoomCloud 管理门户**

登录用户中心，在"您订购的产品" 区域，找到已激活的产品服务。

![](/img/ios/ios-01.png)

点击进入产品详情页面。建议使用 Safari 管理门户，然后点击您的订阅进入订阅详情页面，在「自动配置」功能区点击「节点订阅」，然后在弹出的窗口中选择「普通模式」。点击后，即已经把订阅地址「复制到剪贴板」。

![](/img/ios/ios-02.png)

** 2. 打开 Quantumult 软件，点击「Settings」选项卡，然后点击「Favorites」标签。**

![](/img/ios/quantumult-4.png)

点击右上角的「+」号，并在底部弹出的菜单中选择「Server」

![](/img/ios/quantumult-5.png)

在「Name」中输入「BoomCloud」，然后在「URL」中粘贴刚才复制的节点信息订阅地址。

底部的三个「OPTION」（选项）的功能分别为：

```
「Update Option」：仅更新本地存在的节点。即如果勾选此选项，当一个节点在本地不存在，而节点信息订阅中提供了这个节点，那么这个节点不会被添加到本地。

「Delete Option」：删除本地节点。即如果勾选此选项，当一个由订阅功能提供的节点在下一次订阅更新时不再存在，Quantumult 也会同时删除本地的对应节点。

「Additional Option」：保持本地节点名称。即如果勾选此选项，当一个由订阅功能提供的节点在用户手动更新了节点名称后，即使下一次订阅更新时这个节点名称发生了变化，Quantumult 也不会更新本地节点的名称。
```

用户可以根据自身需求选择这些选项，但 BoomCloud 的官方推荐值是仅勾选「Delete Option」。


点击「Save」，Quantumult 就会返回之前的界面，这时，在刚刚添加的「BoomCloud 」服务器订阅上向左滑动，点击黑色的「Update」按钮，Quantumult 就会请求 BoomCloud API 并获取最新的接入点信息。

![](/img/ios/quantumult-7.png)

成功会弹出提示框显示「Successfully updated」，如果弹出其他提示信息，请联系 BoomCloud 技术支持服务部门。

![](/img/ios/quantumult-8.png)

**添加 TCP Filter** 

点击「Favorites」 进入订阅管理页面，然后点击右上角的 `+`

![](/img/ios/quantumult-10.png)

在弹出的菜单中选择「TCP Filter」

![](/img/ios/quantumult-11.png)

在新的页面中，点击 「Name」，输入 `conf` 并保存，然后点击 「URL」，添加：  

`https://cdn-for-boomcloud.b0.upaiyun.com/quantumult/Default.conf`

同样，在 TCP Filgter 分类下名称为 `conf`的选项上向左轻扫，点击「Replace」。Quantumult 会从静态资源服务器上下载 TCP 规则，并在完成后弹出新页面：

![](/img/ios/quantumult-13.png)

点击 OK 即可。

![](/img/ios/quantumult-4.png)

在「 Server 」选项中选择订阅内线路，在节点列表中可以自由点击切换线路，寻找最适合您的高速线路。

最后切换到「 Home 」,点击 「 Connect」按钮，成功开启BoomCloud加速服务。

![](/img/ios/quantumult-9.png)


