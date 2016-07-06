# 第一节 html/css/js/browser

![](https://raw.githubusercontent.com/leichunhui/testgit/master/r.jpg)

前端要学习三个部分：HTML，CSS，JavaScript（简称JS），因此首先明确三个概念：
HTML是内容层，它的目的是表示一个HTML标签在页面里是个什么角色。 
CSS是样式层，它的目的是表示一块内容以什么样的样式（字体、大小、颜色、宽高等）显示。 
JS是行为层，它要做的是当用户触发某些行为时，会给内容和样式带来什么样的改变。

##1.HTML，CSS部分。
HTML/CSS初学，就照着http://www.w3cschool.cn/的实验做，把http://www.w3cschool.cn/index-6.html 和 http://www.w3cschool.cn/index-7.html 两套做完了就入门了，

入门之后，学习CSS的精华，即布局，推荐李炎恢的教学视频，布局这一章：http://edu.51cto.com/lesson/id-14895.html 第27章，如果觉得不够，需要实战，则再学习接下来的28，29章。注意，这时候一定要老师讲一块代码，自己就要照着实现一次，切勿只看不做。

CSS还有一个精华部分就是命名规范，找几个著名网站（比如豆瓣、网易新闻）这类，研究它们的命名规范，我这里，有一个现成的命名规范可供学习（需要登录evernote查看）：https://www.evernote.com/shard/s168/sh/7f89cc57-cab2-4712-b61b-9fde25e3ef51/d01c8e34ef05373ec06c3b2f7cfaba82/res/e0b9963b-ba7a-441a-8462-8f87c48e4cda.jpg?resizeSmall&width=832 

学习完成后就是一个较为熟练的HTML/CSS使用者了.这时候如果想继续深入学习相关类库和框架，推荐Sass和Compass，推荐两篇阮一峰的博客：http://www.ruanyifeng.com/blog/2012/06/sass.html http://www.ruanyifeng.com/blog/2012/11/compass.html
和这本书：《Sass and Compass in Action》http://book.douban.com/subject/6732187/

##2.JavaScript部分

初学者推荐看视频：http://edu.51cto.com/course/course_id-166-page-1.html ，特别注意JavaScript的OOP写法（重点，可多看几遍），以及闭包、原型链，异步编程部分（次重点），前者写项目都在用，后者涉及JS这个语言本质特点。

然后需要学习JS和HTML/CSS在浏览器下的调试方法，推荐用Google Chrome下的chrome developer tools调试，可以看这个视频学习： http://happycasts.net/episodes/40。

看完视频并经过实践后，可以看《Javascript good parts》（http://book.douban.com/subject/2994925/）这本书，不必细看，看它的思想即可。用于巩固，提升JS方面的编程思想。


**(以上内容参考网址：https://www.douban.com/note/330647290/)**

##3.Browser部分


Browser(浏览器)是指可以显示网页服务器或者文件系统的HTML文件（标准通用标记语言的一个应用）内容，并让用户与这些文件交互的一种软件。
它用来显示在万维网或局域网等内的文字、图像及其他信息。这些文字或图像，可以是连接其他网址的超链接，用户可迅速及轻易地浏览各种信息。大部分网页为HTML格式。

一个网页中可以包括多个文档，每个文档都是分别从服务器获取的。大部分的浏览器本身支持除了HTML之外的广泛的格式，例如JPEG、PNG、GIF等图像格式，并且能够扩展支持众多的插件（plug-ins）。另外，许多浏览器还支持其他的URL类型及其相应的协议，如FTP、Gopher、HTTPS（HTTP协议的加密版本）。HTTP内容类型和URL协议规范允许网页设计者在网页中嵌入图像、动画、视频、声音、流媒体等。

国内网民计算机上常见的网页浏览器有，QQ浏览器、Internet Explorer、Firefox、Safari，Opera、Google Chrome、百度浏览器、搜狗浏览器、猎豹浏览器、360浏览器、UC浏览器、傲游浏览器、世界之窗浏览器等，浏览器是最经常使用到的客户端程序。

###各类浏览器
NCSA Mosaic使互联网得以迅速发展。它最初是一个只在Unix运行的图像浏览器；很快便发展到在Apple Macintosh和Microsoft Windows亦能运行。1993年9月发表了1.0版本。NCSA中Mosaic项目的负责人Marc Andreesen辞职并建立了网景通讯公司。

网景公司在1994年10月发布了他们的旗舰产品网景导航者。但第二年Netscape的优势就被削弱了。错失了互联网浪潮的微软在这个时候匆促的购入了Spyglass公司的技术，改成Internet Explorer，掀起了软件巨头微软和网景之间的浏览器大战。这同时加快了万维网发展。

这场战争把网络带到了千百万普通电脑用户面前，但同时显露了互联网商业化如何妨碍统一标准的制定。微软和网景都在他们的产品中加入了许多互不相容的HTML扩展代码，试图以这些特点来取胜。1998年，网景公司承认其市场占有率已无法挽回，这场战争便随之而结束。微软能取胜的其中一个因素是它把浏览器与其操作系统一并出售（OEM，原始设备制造）；这亦使它面对反垄断诉讼。

网景公司以开放源代码迎战，创造了Mozilla，但此举未能挽回Netscape的市场占有率。在1998年底美国线上收购了网景公司。在发展初期，Mozilla计划为著吸引开发者而挣扎；但至2002年，它已发展成一个稳定而强大的互联网套件。Mozilla 1.0的出现被视为其里程碑。同年，衍生出Phoenix（后改名Firebird，最后又改为Firefox）。Firefox 1.0于2004年发表。及至2008年，Mozilla及其衍生产品约占20%网络交通量。
Opera是一个灵巧的浏览器。它发布于1996年。2013年它在手持电脑上十分流行。它在个人电脑网络浏览器市场上的占有率则稍微较小。

Lynx浏览器仍然是Linux市场上十分流行的浏览器。它是全文字模式的浏览器，视觉上并不讨好。还有一些有着进阶功能的同类型浏览器，例如Links和它的分支ELinks。

Konqueror是一个由KDE开发的浏览器，KDE开发人员在开发KDE2时意识到一个良好的桌面环境必须搭配一个良好的网络浏览器及档案管理员，便投入不少力量开发了Konqueror，这个浏览器使用了自家开发的排版引擎KHTML，由于Konqueror是属于KDE的一员，并只常见于Unix-like下的KDE桌面环境，所以Konqueror并未普及；纵然Macintosh的浏览器市场亦同样被Internet Explorer和Firefox占据，但2013年以后有可能会是苹果电脑自行推出的Safari的世界。Safari是基于Konqueror这个开放源代码浏览器的KHTML排版引擎而制成的。Safari是Mac OS X的默认浏览器。

###微软浏览器的发展

2003年，微软宣布不会再推出的独立的Internet Explorer，但会变成视窗平台的一部分；同时也不会再推出任何Macintosh版本的Internet Explorer。不过，于2005年初，微软却改变了计划，并宣布将会为Windows XP、Windows Server 2003和Windows Vista操作系统推出Internet Explorer 7。

2011年3月15日，微软推出了Internet Explorer9的正式版，值得一提的是，Internet Explorer9不再支持Windows XP。微软官方表示，IE9不支持WindowsXP是因为其硬件加速功能在WindowsXP系统上无法正常运行。而windows7要求电脑内存至少在1G以上。对此，微软大中华区开发工具及平台事业部总经理谢恩伟表示，“建议这部分用户使用IE8。”

2011年4月11日，Internet Explorer9才推出1个月，微软又推出了Internet Explorer10的首个预览版本。Internet Explorer9不支持XP让不少用户感到愤怒，而如今细心的用户在Internet Explorer10平台开发版的最终用户许可协议中看到，Internet Explorer10连Windows Vista系统也不打算支持了。据协议描述，Internet Explorer10将只支持Windows 7 、Windows 8 两个版本，不过好在Windows Vista从开始到结束都是一个悲情故事，Internet Explorer10不支持Windows Vista对于这么点用户数量而言实在是很难引起反弹的。

##Web前端之基础知识
**参考网址：http://blog.csdn.net/bear_huangzhen/article/details/46387863**
##各类程序员学习路线图
**参考网址：http://www.runoob.com/coder-learn-path**
##2016年WEB前端学习误区详解之WEB前端学习路线
**参考网址：http://mt.sohu.com/20160126/n435862702.shtml**
##Web前端工程师职业学习路线图
**参考网址：http://jingyan.baidu.com/article/ca2d939d327edaeb6c31ce89.html**
##web前端开发学习路线
**参考网址：http://www.aseoe.com/show-41-582-1.html**