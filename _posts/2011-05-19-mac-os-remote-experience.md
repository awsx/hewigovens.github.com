---
comments: true
date: 2011-05-19 23:21:08
layout: post
slug: mac-os-x%e8%bf%9c%e7%a8%8b%e4%bd%93%e9%aa%8c
title: Mac OS X远程体验
wordpress_id: 253
categories:
- iOS
tags:
- mac os x
- vnc
---

在V2ex偶然发现了苹果派的[免费os X远程体验环境即将推出，开放预约](http://www.a-pie.com/2011/04/%E5%85%8D%E8%B4%B9os-x%E8%BF%9C%E7%A8%8B%E4%BD%93%E9%AA%8C%E7%8E%AF%E5%A2%83%E5%8D%B3%E5%B0%86%E6%8E%A8%E5%87%BA%EF%BC%8C%E5%BC%80%E6%94%BE%E9%A2%84%E7%BA%A6/)这个帖子，就预约了，其实我主要是想看下pppoe在mac底下命令行是如何配置的。算起来当年也和小唐子折腾过一阵子黑苹果，在家的台式机也装过10.4.7，后来装显卡驱动挂掉了，再后来就是在虚拟机上和苹果体验店。还没有远程体验过mac。这个环境配置用的是vnc，我最早是在用rhel的时候用过，不过现在都是直接ssh了。

 

我使用的客户端是开源的tightvnc，注意选择High-speed network，见下图，这是最省事的方法，这个选项主要是为了打开全屏，否则连上后屏幕会一闪而过。

 

<a href="http://s750.photobucket.com/user/hewigovens/media/wp-migrate/uploads/2011/05/image2_zps7ede537a.png.html" target="_blank"><img src="http://i750.photobucket.com/albums/xx144/hewigovens/wp-migrate/uploads/2011/05/image2_zps7ede537a.png" width=100% border="0" alt=" photo image2_zps7ede537a.png"/></a>

 

输入用户名密码，登录。

 

<a href="http://s750.photobucket.com/user/hewigovens/media/wp-migrate/uploads/2011/05/image3_zps876dee5a.png.html" target="_blank"><img src="http://i750.photobucket.com/albums/xx144/hewigovens/wp-migrate/uploads/2011/05/image3_zps876dee5a.png" width=100% border="0" alt=" photo image3_zps876dee5a.png"/></a>

 

可以看到，安装的是10.5.2，CPU是AMD的，这和在intel x86机器上装mac没什么区别，皓龙支持的指令集就包括x86。

 

<a href="http://s750.photobucket.com/user/hewigovens/media/wp-migrate/uploads/2011/05/image4_zps8df6fb84.png.html" target="_blank"><img src="http://i750.photobucket.com/albums/xx144/hewigovens/wp-migrate/uploads/2011/05/image4_zps8df6fb84.png" width=100% border="0" alt=" photo image4_zps8df6fb84.png"/></a>

 

现在对OS的没什么特别的要求，因为很多服务都可以通过浏览器来搞定，10.5.2自带的是safari 3，传说中的safari reader mode好像在5.0版本才支持。

 

<a href="http://s750.photobucket.com/user/hewigovens/media/wp-migrate/uploads/2011/05/image5_zps9d857f42.png.html" target="_blank"><img src="http://i750.photobucket.com/albums/xx144/hewigovens/wp-migrate/uploads/2011/05/image5_zps9d857f42.png" width=100% border="0" alt=" photo image5_zps9d857f42.png"/></a>

 

也不支持mac app store，snow leopard才支持。

 

<a href="http://s750.photobucket.com/user/hewigovens/media/wp-migrate/uploads/2011/05/image6_zps4f466612.png.html" target="_blank"><img src="http://i750.photobucket.com/albums/xx144/hewigovens/wp-migrate/uploads/2011/05/image6_zps4f466612.png" width=100% border="0" alt=" photo image6_zps4f466612.png"/></a>

 

dashboard，widget平铺的效果很华丽；dock就不用说了吧

 

<a href="http://s750.photobucket.com/user/hewigovens/media/wp-migrate/uploads/2011/05/image7_zps9e6462d1.png.html" target="_blank"><img src="http://i750.photobucket.com/albums/xx144/hewigovens/wp-migrate/uploads/2011/05/image7_zps9e6462d1.png" width=100% border="0" alt=" photo image7_zps9e6462d1.png"/></a>

 

似乎默认没有装pppoe或者pon，由于没有权限本来想使用下安装和使用下macports或者homebrew的，终端感觉没有gnome-terminal或者konsole好用。。

 

<a href="http://s750.photobucket.com/user/hewigovens/media/wp-migrate/uploads/2011/05/image8_zps22759386.png.html" target="_blank"><img src="http://i750.photobucket.com/albums/xx144/hewigovens/wp-migrate/uploads/2011/05/image8_zps22759386.png" width=100% border="0" alt=" photo image8_zps22759386.png"/></a>

 

Application目录下有不少应用程序，其中Textmate被誉为mac下最好用的编辑器之一。

 

<a href="http://s750.photobucket.com/user/hewigovens/media/wp-migrate/uploads/2011/05/image9_zpscb0077e2.png.html" target="_blank"><img src="http://i750.photobucket.com/albums/xx144/hewigovens/wp-migrate/uploads/2011/05/image9_zpscb0077e2.png" width=100% border="0" alt=" photo image9_zpscb0077e2.png"/></a>

 

不过windows底下有替代品~

 
<a href="http://s750.photobucket.com/user/hewigovens/media/wp-migrate/uploads/2011/05/image10_zps054db17d.png.html" target="_blank"><img src="http://i750.photobucket.com/albums/xx144/hewigovens/wp-migrate/uploads/2011/05/image10_zps054db17d.png" width=100% border="0" alt=" photo image10_zps054db17d.png"/></a>

 

自带了ruby,python,java等环境，再mac底下写code应该蛮爽的

 

<a href="http://s750.photobucket.com/user/hewigovens/media/wp-migrate/uploads/2011/05/image11_zps57c9aa16.png.html" target="_blank"><img src="http://i750.photobucket.com/albums/xx144/hewigovens/wp-migrate/uploads/2011/05/image11_zps57c9aa16.png" width=100% border="0" alt=" photo image11_zps57c9aa16.png"/></a>

 

体验到这一步就结束了吧，远程连上去有点卡，像播放slide一样，而且mac的不仅仅是mac os x而已，因为苹果现在仍然是软硬都做，mac机器细节部分做的很好，总而言之，mac os x还是值得尝试的。

 

再次感谢Michael Won和提供的体验环境~
