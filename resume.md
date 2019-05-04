# 个人简历  

## 联系方式
* 手机：18540279973(沈阳)  

* Email：`come.ydq@gmail.com`  

* 微信号：CEO160405222  

## 个人信息
* 杨道青 / 男 / 1998  

* 毕业学校：沈阳工业大学 / 信息科学与工程学院 / 计算机科学与技术  

* GitHub：[`https://github.com/MapCy`](https://github.com/MapCy)  

## 技能清单<br>
* 语言：Java / C++ / C  

* 前端：JavaScript / HTML / Jquery / CSS  

* 数据库：MySQL / SQLServer

* 后端框架：Spring+SpringMVC+Mybatis  

* 操作系统：熟练使用Linux常用操作命令，业余管理一台Linux腾讯云服务器，一台Windows阿里云服务器。  

* 安卓开发：熟悉Android开发，并有两个项目的开发经验，见*项目经历*。   

* 视觉识别：熟悉OpenCV及基本的图像处理,并实现了"装甲识别"，见*项目经历*。  

* 版本管理：Git  

* 其它：正则表达式 / Maya / Unity3D  

## 项目经历
>&emsp;&emsp;以下项目虽然简单，但基本涵盖了我从大一到现在做过的所有东西，见证了自己的成长。

* 小当家PettyMan
> `Situation`：“小当家”是一款安卓购物app，大致分为学习和购物两大功能（利用学习获得的奖励金币进行商品购买），包含基本的登录注册、商品浏览、购买、支付、个人中心、收货地址编辑以及学习计时等功能。  
> `Task`：负责应用的整体设计，以及建立后台数据库、编写布局文件、功能类的开发和测试等工作。  
> `Action`：使用Visio设计数据库(E-R图)，采用安卓内嵌数据库SQLite完成数据库开发。在Windows平台下利用eclipse编写布局文件、活动类、工具类，期间采用AndroidTestCase实现函数功能测试。  
> `Result`：编写了5个包，32个类，完成了13个Activity的开发，实现了系统设计之初90%的功能。21个布局文件的开发，涵盖了小当家应用的所有交互界面。

1. <font size="4px"><kbd>`iwatch`智能手表</kbd></font>

    - <font size="3px">项目介绍</font>&emsp;
该系统包含计步、拨打电话、管理联系人(添加、删除、查找、修改)、计算`BMI`健康指数等功能，模拟了拨打电话、接听电话的过程，以及心率计算、步行排行榜。


    - <font size="3px">实现</font>&emsp;
`C++`编程，系统分三个模块开发（联系人、健康指标计算、计步）。通讯录采用文件形式存储（当时还没学过数据库，所以采用了最简单的文件存储），联系人的增删改查都是直接针对文件操作。界面是纯粹的黑色控制台，采用键盘输入的方式实现交互。

    - <font size="3px">感悟</font>&emsp;
虽然还是最原始的黑色控制台，包含的功能也不多，很多炫酷的功能都只是模拟实现。但这是自己在学习完《`C++`程序设计》这门课后所做的东西，对一个大二上学期，对计算机科学与技术这个专业还一头雾水的我来说，还是比较满意。

    - <font size="3px">项目地址</font>&emsp;
[`智能手表`](https://github.com/MapCy/practice/tree/master/iwatchScreen)

2. 小当家app</font>
    - <font size="3px">项目介绍</font>&emsp;


    - <font size="3px">实现</font>&emsp;
`java`编程，采用安卓开发的技术，利用`SQLite`数据库存储数据。

    - <font size="3px">感悟</font>&emsp;
尽管自己很喜欢`C/S`开发模式，喜欢那种动态的、一直在变化的、给人新颖感觉的交互方式，喜欢井然有序的前后端分开开发，以及对后台强大处理能力的好奇。但由于技术有限，只得采用静态的、本地的方式，开发这款`app`，既是给自己学习`Android`开发的一个交代，也是为学习`C/S`开发做一个铺垫吧！

    - <font size="3px">项目地址</font>&emsp;
[`小当家`](https://github.com/MapCy/practice/tree/master/Eat)

3. <font size="4px"><kbd>装甲识别</kbd></font>
    - <font size="3px">项目介绍</font>&emsp;
`C++`编程，这是我`2018`年`5`月参加机甲大师比赛，负责视觉识别所做的项目。目的是识别机器车上的`LED`灯条，分辨敌我，完成自动瞄准、射击的功能。

    - <font size="3px">实现</font>&emsp;
利用`OpenCV`开源框架，对摄像头采集的数据进行处理，具体的实现方法、采用的处理过程见《[机甲大师视觉识别项目总结](https://github.com/MapCy/techDoc)》文档。

    - <font size="3px">感悟</font>&emsp;
此次比赛，让我接触到了计算机视觉，见到了“实体”程序的魅力，不再是黑色的控制台。总而言之，这个项目让我学会了基本的图像处理技术，感受到了计算机视觉的魅力，领略到了`OpenCV`的强大。我，还会继续`OpenCV`的学习！

    - <font size="3px">项目地址</font>&emsp;
[`机器车装甲识别`](https://github.com/MapCy/practice/tree/master/arromrDetect)

4. <font size="4px"><kbd>风电场监控</kbd></font>
    - <font size="3px">项目介绍</font>&emsp;
这也是一款安卓`app`，是继“小当家”之后和《`Javaweb`程序设计》课程完结所做的一款产品（完善中）。以部署在阿里云上的`web`服务器为后端，开发的风电场监控移动应用。该应用具有数据监控、报修、紧急联系监控中心、生成调度策略等功能。

    - <font size="3px">实现</font>&emsp;
`Java`编程，`eclipse`开发后端（`SSM`框架），部署`Maven`工程到阿里云服务器上。利用安卓网络开发访问服务器，实现数据更新、交互。

    - <font size="3px">感悟</font>&emsp;
这是在“小当家”之后做出的对C/S开发模式的探索(更多的是向往)，虽然项目还在完善中，但还是感谢自己愿意探索、愿意尝试的态度。加油，`myself!`

    - <font size="3px">项目地址</font>&emsp;
[`风电场监控服务端`](https://github.com/MapCy/practice/tree/master/workSpace/moon-manager)


## 参赛经历
1. 专业相关
    - 大学生创新创业大赛，获得“互联网+”校级证书；
   
    - 第十二届`ACM`程序设计竞赛；
   
    - 参加“`ROBOMASTER 2018`机甲大师”，获得全国三等奖；

    - 信息学院电子设计大赛；

2. 文体相关
    - 沈阳工业大学第五十二届田径运动会，获得“男子`400`米栏第七名”；
  
    - 信息科学与工程学院“金音天籁，麦动信息”杯主持人大赛，获得“优秀奖”；
    
    - 沈阳工业大学第五十三届田径运动会，获得“男子`400`米栏第六名”



## 嘉奖及证书

* “优秀军训学员”证书
* 英语四级证书
* 英语六级证书
* 中软国际`2018`年度寒假训练营“卓越个人奖”
* “`RoboMaster`全国机甲大师”全国三等奖证书
* 国家励志奖学金
* “三好学生”称号
* 大创项目“`Microlaw`微法”证书
* “男子`400`米栏”证书
<br>

[`证书展示`](https://github.com/MapCy/resume/blob/master/award.jpg)



## 求职意向
><kbd>研发类</kbd> `Java`后端开发、`C/C++`、`Android`

