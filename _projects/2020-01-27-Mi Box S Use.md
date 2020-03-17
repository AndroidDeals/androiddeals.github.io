---
layout: post
title:  "小米盒子国际版/Mi Box S入门指南"
date:   2020-01-27 0:52:21 -0500
categories: 原生安卓TV
top: true 

---
# 它的使用步骤是什么？
Mi Box S本质上就是电视盒子，只不过没有国产盒子那么多的广告植入。
1. 首次开机激活，连上可以科学上网(例如`openwrt、梅林、官改`)固件的路由器，登录谷歌账号激活设备。
2. 激活之后，进入主界面。打开你想看的应用，登录其账号开始观看。
![preview](https://raw.githubusercontent.com/AndroidDeals/AndroidDeals.github.io/master/Screenshots/mihome.png)


<HR>
 
# 某些应用在谷歌自带的应用市场并不能下载到，怎么办？请看下面的内容。
## Android TV上非常好用的第三方软件

* Smart Youtube TV[点击下载](https://github.com/yuliskov/SmartYouTubeTV/releases/download/stable/smartyoutubetv_latest.apk)大名鼎鼎的第三方YouTube应用，可看4K，没有广告，来自[yuliskov](https://github.com/yuliskov/SmartYouTubeTV)。

* SSR[点击下载](https://github.com/AndroidDeals/AndroidDeals.github.io/releases/download/2019.12.17/shadowsocksr-android-3.6.0-fix.apk)，最广泛使用的科学上网工具。需要注意的是，`添加订阅的时候需要配合蓝牙蓝牙蓝牙鼠标`。


* FireFox浏览器[点击下载](https://github.com/AndroidDeals/AndroidDeals.github.io/releases/download/2019.12.17/firefox_4.6.apk)谷歌商店没什么好用的网页浏览器，可以安装这个用一用。

* Nplayer[点击下载](https://github.com/AndroidDeals/AndroidDeals.github.io/releases/download/2019.12.17/nPlayer.v1.7.7.7_191219.armeabi-v7a.apk)，一款非常优秀的本地视频播放器，支持多种解码方式，来自[nplayer](https://nplayer.com/)这个网站。

* Perfect Player[点击下载](https://github.com/AndroidDeals/AndroidDeals.github.io/releases/download/2019.12.17/Perfect-Player.apk)非常好用的电视直播播放器，可以根据自己的需要去添加IPTV信号源。

* IPTV Pro[点击下载](https://github.com/AndroidDeals/AndroidDeals.github.io/releases/download/2019.12.17/iptv-pro.apk)也是一种常用的电视直播播放器，界面非常简洁，添加IPTV信号源即可观看。

* 文件管理器+，韩国人开发的一款文件管理器，测试感觉还是不错的，[点击下载](https://github.com/AndroidDeals/AndroidDeals.github.io/releases/download/2019.12.17/filemanager+.apk)

<HR>
 
## Android TV安装第三方软件常用的几种方法
注意一点，必须先从谷歌市场下载一款名叫`Sideload Launcher`的应用。因为国内的很多应用不遵守leanback框架，所以在Android TV主页不会显示出来，而这个应用可以把所有已经安装的应用都显示出来，界面如下。
![preview](https://raw.githubusercontent.com/AndroidDeals/AndroidDeals.github.io/master/Screenshots/sideloadlauncher.png)

方法提供两种，方式如下
1. [通过U盘安装。](#jump1)
2. [PC端-通过ADB命令安装。](#jump2)

## <span id="jump1">U盘安装</span>
1. 把想安装的Apk应用下载好放进U盘，谷歌市场下载一个文件管理器。
2. 将U盘插入小米盒子，打开文件管理器，找到下载的应用安装即可。


## <span id="jump2">PC端安装工具-ADBLink的使用方法</span>

* ADBlink来自[jocala](http://www.jocala.com/)这个网站。
  * MacOS版[点击下载](https://github.com/AndroidDeals/AndroidDeals.github.io/releases/download/2019.12.17/adblink42-Macos.dmg)
  * Windows版[点击下载](https://github.com/AndroidDeals/AndroidDeals.github.io/releases/download/2019.12.17/adblink42-Win.exe)

1. 首先保证电脑和Mi Box S连接同一个网络，选择界面右上角设置图标，往下找到关于，点进去。
![preview](https://raw.githubusercontent.com/AndroidDeals/AndroidDeals.github.io/master/Screenshots/m1.png)

### 这时我们找到内部版本号，连续点击，会提示你再点击几次之后会拥有开发者选项。成功之后再返回设置，就可以看到开发者选项这一栏了。
![preview](https://raw.githubusercontent.com/AndroidDeals/AndroidDeals.github.io/master/Screenshots/m2.png)

![preview](https://raw.githubusercontent.com/AndroidDeals/AndroidDeals.github.io/master/Screenshots/m3.png)

### 随即往下找到USB调试，大功告成啦。这时候，就可以用ADB工具进行安装第三方应用操作了。
![preview](https://raw.githubusercontent.com/AndroidDeals/AndroidDeals.github.io/master/Screenshots/m4.png)

2. 打开ADBlink这个应用，新增设备。各平台版本几乎没有差别。
### 如图所示：
![preview](https://raw.githubusercontent.com/AndroidDeals/AndroidDeals.github.io/master/Screenshots/3.png)
![preview](https://raw.githubusercontent.com/AndroidDeals/AndroidDeals.github.io/master/Screenshots/4.png)

3. 这个时候点击connect，接下来电视机上会显示新设备认证，选择allow。允许之后，就连接成功了。
![preview](https://raw.githubusercontent.com/AndroidDeals/AndroidDeals.github.io/master/Screenshots/5.png)
![preview](https://raw.githubusercontent.com/AndroidDeals/AndroidDeals.github.io/master/Screenshots/6.jpg)

4. 点击install APK，跳出文件夹，直接选择想要安装的apk应用安装就可以了。安装完成之后电视机右下角会有成功提示。
![preview](https://raw.githubusercontent.com/AndroidDeals/AndroidDeals.github.io/master/Screenshots/7.png)

实际上这个应用功能不止如此，大家可以自己发掘。

