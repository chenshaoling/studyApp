# studyApp
基于html5+mui+hbuilder的移动app




这个项目涉及的技术有：

无所不能的js：

最开始js仅仅局限于网页上一些效果，操作网页内容等，

但是nodejs把js带入了后端，也就是服务器端，从此前端人员可以涉及后端，前后通吃，

native.js（以及其他js，稍候介绍）把js带入了移动端，从此前端人员前后移动通吃。


前端涉及app的两种方式：

1.适应移动端的网页

大家都很熟悉的bootstrap，和现在刚出来的amazeui就是这种方法的代表，

说的简单点就是对移动端做了适配，是的布局样式组件都适合移动端展示，

我的个人网站（uikoo9.com）就是使用bootstrap3做的，手机浏览效果也很好。

缺陷：毕竟不是app，不管怎么样也没办法取代app的便捷和功能强大。

2.js+html+css+打包技术

比较有名的就是phonegap了，国内的是hbuilder，

大概的意思是html负责页面内容，js负责效果以及调用原生app方法，ui框架负责样式，

最后打包成apk或者ipa。


hbuilder（http://www.dcloud.io/）：

不谈phonegap，不适用国内国情，

是的，你没有看错，这是一个开发的ide，其实就是对eclipse进行了深度定制。

特点是快捷键比较多，支持移动app开发（h5+方式）。


h5+（http://www.html5plus.org/#home）：

终于说到正题了，这个就是之前提到的打包技术，

可以说nodejs将js带到后端，h5+将js带到移动端。



原理:

上面说过的原理，再次说一遍：

html负责页面，也就是的内容和框架；

js负责调用方法，也就是调用一些移动端原生；

ui负责样式，比较有名的bootstrap，amazeui，jQuery mobile，mui


ui比较:
上面说的几个ui，做下简单比较，仅代表个人观点，

amazeui，功能和bootstrap重复，官方解释是对中文排版做了优化，个人觉得有点多余，bootstrap就很好。

bootstrap，适合移动端浏览网页适配，移动端浏览效果不错，但是还是网页。

jquery mobile，专门对移动端做定制，看起来就像手机应用一样，js+css（300k），国外的，不推荐，有坑。

mui，这个是推荐的，比较了jqmobile和mui，显然mui效果样式好点，估计也会有坑，但是支持国产吧。


前端搞app:

1.搭建开发环境

不需要搭建iOS和Android的开发环境，只需要下载hbuilder（估计需要Java环境支持），

2.选定ui

目前推荐mui，效果不错

3.写事件

通过js调用原生方法实现app效果

4.写业务逻辑

如题

调试:

手机连接电脑，然后在hbuilder下运行——手机运行——在设备上运行，

就直接可以在手机上看效果了

打包:

在hbuilder中发型——app打包，然后交给云端去打包，打包好后会自动下载


现在，如果你会html+js+css，那你只需要一个hbuilder就可以开发app了，通吃android和ios
