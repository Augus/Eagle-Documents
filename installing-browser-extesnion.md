# 安装并使用浏览器扩展收藏图片

---

### 关于 Eagle 浏览器扩展插件 {#installing-extensions}

身为设计师的你肯定时常在网站上查看到值得收藏的图片、设计，Eagle 浏览器扩展能够让你迅速的将这些看到的图片，以迅雷不及掩耳的速度，收藏到你的图片库中。

---

### 安装浏览器扩展（缺连结）

Eagle 浏览器扩展可以安装到各种浏览器上，本文以 Chrome 为例，介绍如何安装，安装分是大致可以分成两种，分别是「谷歌扩展商店安装」及「手动安装」两种，如果可能的话，**我们强烈建议你从谷歌官方扩展商店安装插件**，不仅安装上最容易，未来也能享有扩展自动更新的好处。

如果你是用的是其他浏览器，你可以点击下方连结查看安装方式：

\[这里缺少一个连结\]

#### 一、谷歌扩展商店安装 Eagle 浏览器扩展

从如果你想要从谷歌官方扩展商店安装，你的网路环境必需要能够连线上谷歌的服务（需要代理工具），安裝方式非常的簡單，首先開啟 Eagle 谷歌扩展商店连结。

步骤一：開啟 Eagle 谷歌扩展连结

[https://chrome.google.com/webstore/detail/eagle/lieogkinebikhdchceieedcigeafdkid](https://chrome.google.com/webstore/detail/eagle/lieogkinebikhdchceieedcigeafdkid)

步骤二：点击画面右上角「添加至 CHROME」按钮，完成安装。![](/assets/eagle-install-chrome-extension.png)

---

#### 二、手动安装 Eagle 浏览器扩展

如果你所在的环境无法正常使用谷歌服务，你可以下载浏览器扩展文件（.crx ）来安装 Eagle 扩展。

步骤一：前往 Eagle 扩展下载页面：

[https://cn.eagle.cool/extensions](https://cn.eagle.cool/extensions)

步骤二：点击「下载 .crx 文件」右键，并点击「另存文件...」，选择位置后下载![](/assets/eagle-chrome-extension-install-manual.png)步骤三：下载完成后，开启扩展文件的路径

步骤四：开启扩展管理页面，你可以直接在网址列输入：[chrome://extensions/](chrome://extensions/) 前往（点击右上角选单 &gt; 更多工具 &gt; 扩展程序）。

步骤五：将 eagle-extension.crx 文件拖拽至扩展管理页面，完成安装。

![](https://github.com/Augus/Eagle-Documents/blob/master/assets/eagle-extension-tips.gif?raw=true)

---

### Eagle 浏览器扩展有哪些功能？

目前 Eagle 浏览器扩展提供四大功能，分别是

1. ##### 单张图片秒速收藏

   随时随地点击网页上看到图片「**Alt + 右键」**就能迅速将图片收藏到 Eagle，除此之外你也可以「**直接拖拽」**眼前的图片到下方拖盘中进行收藏，非常的高效。

2. ##### 网页图片批量收藏

   一张一张收藏很麻烦吗？别担心你可以点击 Eagle 浏览器扩展按钮，选择「**收藏图片**」按钮，直接批量将图片收藏到你的图片库中。  
   ![](https://github.com/Augus/Eagle-Documents/blob/master/assets/extension_batch_collect.gif?raw=true)

3. ##### 网页整页截图

   点击 Eagle 浏览器扩展按钮，选择「整页截图」按钮，迅速将网页整页截图并添加到图片库里面。  
   ![](https://github.com/Augus/Eagle-Documents/blob/master/assets/extension_entrie_capture.gif?raw=true)

4. ##### 网页局部截图

   与整页截图相似，你可以框选截取网页让任何一你想要截取的部分，收藏下来的截图都会保留网站的标题与来源网址，未来查找来源变得非常超容易。

---

### 为什么浏览器扩展点击没有反应？ {#extension}

主要的原因是「**代理软件阻挡了软件与扩展之间的连接**」。Eagle 的浏览器扩充插件主要透过本机地址127.0.0.1/localhost与软件进行沟通，通常出现这个状况是因为你正在使用的代理软件（如 Shadowsocks）将这个地址给遮蔽导致，你可以尝试以下几中方式解决：

* 试试重启 Eagle 软件。
* 将代理软件的代理模式模式设置「**自动代理**」有些软件上叫做 PAC。
* 设置代理软件代理的地址，将本机地址**127.0.0.1**排除。
* 你在使用**Shadowsocks**的话 ，更新下一个世代版本的 ShadowsocksX-NG 能解决这个问题（[macOS下载](https://github.com/shadowsocks/ShadowsocksX-NG/releases) / [Windows下载](https://github.com/shadowsocks/shadowsocks-windows/releases)）。



