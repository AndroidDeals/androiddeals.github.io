---
layout: post
title:  "亚马逊Fire TV Stick教程/火柴棍入门指南"
date:   2019-12-17 18:52:21 -0500
categories: 亚马逊火柴棍
top: true 

---
# 它的使用步骤是什么？
Fire TV本质上就是电视盒子，只不过没有国产盒子那么多的广告植入。
1. 首次开机激活，连上无线网络，登录Amazon(支持`美国，日本，英国，加拿大，印度`)账号
2. 激活之后，进入主界面。打开你想看的应用，登录其账号开始观看。

<HR>
 
# 某些应用在Amazon自带的应用市场并不能下载到，怎么办？请看下面的内容。
## Fire TV上非常好用的第三方软件

* Smart Youtube TV[点击下载](https://github.com/yuliskov/SmartYouTubeTV/releases/download/stable/smartyoutubetv_latest.apk)大名鼎鼎的第三方YouTube应用，可看4K，没有广告，来自[yuliskov](https://github.com/yuliskov/SmartYouTubeTV)。

* SSRR[点击下载](https://github.com/AndroidDeals/AndroidDeals.github.io/releases/download/2019.12.17/SSRR-3.5.4.apk)，最广泛使用的科学上网工具，来自[Akkariiin](https://github.com/shadowsocksrr/shadowsocksr-android/releases)。

* Nplayer[点击下载](https://github.com/AndroidDeals/AndroidDeals.github.io/releases/download/2019.12.17/nPlayer.v1.7.7.7_191219.armeabi-v7a.apk)，一款非常优秀的本地视频播放器，支持多种解码方式，来自[nplayer](https://nplayer.com/)这个网站。

* Perfect Player[点击下载](https://github.com/AndroidDeals/AndroidDeals.github.io/releases/download/2019.12.17/Perfect-Player.apk)非常好用的电视直播播放器，可以根据自己的需要去添加IPTV信号源。

* 添加新电视机和连接蓝牙设备的视频教程以及`ADB安装第三方应用`的教程请戳[这里](https://drive.google.com/open?id=1rTUeXJX8zQlmNUGqomyMLMwmMuaG9I8M)。

<HR>
 
## 为什么你的Fire TV账号不能下载应用？
一个完全可用的账号需要具备以下几个要素（仅以`美国`账号为例）：
1. 账号的国家`必须是美国的`
2. 必须设置一个`美国`的`默认收货地址`
3. 删除掉所有的支付方式

以上三个条件必须全部符合，才可以确保下载应用成功。

<HR>
 
## Fire TV安装第三方软件常用的几种方法
方法分为三种，方式如下
1. [手机端（安卓系统）-通过easyfiretools或者apps2fire等软件推送安装。](#jump1)
2. [机顶盒端-通过商店自带的Downloader上下载应用安装。](#jump2)
3. [PC端-通过ADB命令安装。](#jump3)

## <span id="jump1">安卓手机端推送应用安装</span>
1. 首先保证电脑和火柴棍连接同一个网络，打开 fire tv，选择Settings -> My Fire TV -> Developer Option。然后打开 ADB debugging 和 Apps from Unknowing Sources 选项。
2. 安卓手机端安装应用Easy Fire Tools[点击下载](https://github.com/AndroidDeals/AndroidDeals.github.io/releases/download/2019.12.17/Easy.Fire.Tools.apk)
3. 打开Easy Fire Tools，点击右上角符号，查找局域网内的火柴棍，
### 如图所示：![eft](https://raw.githubusercontent.com/AndroidDeals/AndroidDeals.github.io/master/Screenshots/eft1.png)
4. 选择火柴棍，选择之后再点击对接logo
### 如图所示：![eft](https://raw.githubusercontent.com/AndroidDeals/AndroidDeals.github.io/master/Screenshots/eft2.png)![eft](https://raw.githubusercontent.com/AndroidDeals/AndroidDeals.github.io/master/Screenshots/eft3.png)
5. 电视机上会显示新设备认证，选择allow。
### 如图所示：![preview](https://raw.githubusercontent.com/AndroidDeals/AndroidDeals.github.io/master/Screenshots/6.jpg)
允许之后，右上角对接logo变绿并且连接成功。
### 如图所示：![eft](https://raw.githubusercontent.com/AndroidDeals/AndroidDeals.github.io/master/Screenshots/eft4.png)
6. 选择自己想要安装的应用安装即可
### 如图所示：![eft](https://raw.githubusercontent.com/AndroidDeals/AndroidDeals.github.io/master/Screenshots/eft5.png)
这个应用的功能很强大，大家自行发掘。



## <span id="jump2">Fire TV神器Downloader（机顶盒上直接操作）</span>
这个神器的优点就是全程可以在火柴棍上直接下载应用并安装，适合新手。

1.到亚马逊商店下载这个应用，直接搜索Downloader
### 来个图标看一下。
![preview](https://raw.githubusercontent.com/AndroidDeals/AndroidDeals.github.io/master/Screenshots/d1.png)

2.打开 fire tv，选择Settings -> My Fire TV -> Developer Option。然后打开 Apps from Unknowing Sources 选项。

3.打开Downloader这个软件，如果你知道想下载软件的直接下载链接，那么直接输入，即可完成下载安装
### 就像这样：
![preview](https://raw.githubusercontent.com/AndroidDeals/AndroidDeals.github.io/master/Screenshots/d2.png)
![preview](https://raw.githubusercontent.com/AndroidDeals/AndroidDeals.github.io/master/Screenshots/d4.png)
![preview](https://raw.githubusercontent.com/AndroidDeals/AndroidDeals.github.io/master/Screenshots/d5.png)

4.如果你并不知道软件的直接下载地址，那么就使用Downloader内置的浏览器进行下载安装。比如说我们想下载当贝市场，那么我们通过浏览器到当贝市场的主页，找到下载应用的选项卡，点击之后，自动下载应用，进行安装。大功告成！
### 如图所示：
![preview](https://raw.githubusercontent.com/AndroidDeals/AndroidDeals.github.io/master/Screenshots/d3.png)
![preview](https://raw.githubusercontent.com/AndroidDeals/AndroidDeals.github.io/master/Screenshots/d4.png)
![preview](https://raw.githubusercontent.com/AndroidDeals/AndroidDeals.github.io/master/Screenshots/d5.png)



## <span id="jump3">PC端安装工具-ADBLink的使用方法</span>

* ADBlink来自[jocala](http://www.jocala.com/)这个网站。
  * MacOS版[点击下载](https://github.com/AndroidDeals/AndroidDeals.github.io/releases/download/2019.12.17/adblink42-Macos.dmg)
  * Windows版[点击下载](https://github.com/AndroidDeals/AndroidDeals.github.io/releases/download/2019.12.17/adblink42-Win.exe)

1.首先保证电脑和火柴棍连接同一个网络，打开 fire tv，选择Settings -> My Fire TV -> Developer Option。然后打开 ADB debugging 和 Apps from Unknowing Sources 选项。

### 如图所示：
![preview](https://raw.githubusercontent.com/AndroidDeals/AndroidDeals.github.io/master/Screenshots/1.png)

2.选择Settings -> My Fire TV -> About -> Network，记住机子的IP地址。
### 如图所示：
![preview](https://raw.githubusercontent.com/AndroidDeals/AndroidDeals.github.io/master/Screenshots/2.png)

3.打开ADBlink这个应用，新增设备。各平台版本几乎没有差别。
### 如图所示：
![preview](https://raw.githubusercontent.com/AndroidDeals/AndroidDeals.github.io/master/Screenshots/3.png)
![preview](https://raw.githubusercontent.com/AndroidDeals/AndroidDeals.github.io/master/Screenshots/4.png)

4.这个时候点击connect，接下来电视机上会显示新设备认证，选择allow。允许之后，就连接成功了。
![preview](https://raw.githubusercontent.com/AndroidDeals/AndroidDeals.github.io/master/Screenshots/5.png)
![preview](https://raw.githubusercontent.com/AndroidDeals/AndroidDeals.github.io/master/Screenshots/6.jpg)

5.点击install APK，跳出文件夹，直接选择想要安装的apk应用安装就可以了。安装完成之后电视机右下角会有成功提示。
![preview](https://raw.githubusercontent.com/AndroidDeals/AndroidDeals.github.io/master/Screenshots/7.png)

实际上这个应用功能不止如此，大家可以自己发掘。

