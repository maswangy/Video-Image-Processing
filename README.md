# Video-Image-Processing



[![GitHub issues](https://img.shields.io/github/issues/TongxinV/Video-Image-Processing.svg)](https://github.com/TongxinV/Video-Image-Processing/issues)


doing


还在进行...

####2017-02-17 10:56:48


该项目主要还是在应用层上的实现，之前基于v4l2的摄像头采集程序是用C语言实现的，也曾用C语言写过一个简单的应用程序。现在不想用C语言编写应用程序了，第一：想重新学习下C++，一直在学习嵌入式驱动开发，C语言接触得比较多，也一直在用C语言，偶尔换换口味还是很有必要的；第二：个人理解随着嵌入式CPU性能的提高已经能够使C++语言在开发板上能够流畅运行，而且应用程序方面使用C++也是比较主流的一种做法；第三：很多库支持C++接口更加丰富，如将来需要使用的opencv库，它的一些新特性都是C++ 接口。


网上搜索了嵌入式纯C++应用开发，很少，大部分是qt。开发项目的功能实现是可以不用GUI的，不想程序那么笨重。qt/Embedded是通过QtAPI与Linux I/O以及Framebuffer直接交互，即它要能够显示或者触摸功能显示肯定要跟设备文件打交道，那我参考它这些功能实现就OK了，那就要去参考看源码咯，qt源码好像没找到，也没认真找。之前看过韦东山编著的《嵌入式Linux应用开发完全手册》中的第25章对嵌入式Linux中的几种GUI的介绍，了解到qte。在githup上找到了源码(8年前的源码...)，这个代码量比较少，应该比较好理解。通过关键字搜索它对显示这一块的封装，结果和之前的猜测一样，和之前用C语言实习的方式一样。


解决了心中的疑惑的，下一步就是重新拾起C++了:muscle:



####2017-02-17 16:25:35

偶然想起家里的路由器，也是没有界面的，设置的时候是通过网页来实现的，这种设计思路是什么呢？要自己能够开发还需要掌握哪些知识呢？:confused:

----
author：@TongxinV



