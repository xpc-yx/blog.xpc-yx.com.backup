---
title: 吐槽下cgal
tags:
  - CGAL
id: 853
categories:
  - 图形学
  - CGAL
date: 2013-07-26 15:20:27
---

cgal是计算几何算法库的意思。是用c++模板写成的。虽然，我用了几年c++，但是对模板不太熟悉，况且代码实在太复杂，看不懂。。。
cgal使用起来确实比较麻烦，都是模板，语法多了很多。添加自己的功能的话，还得继承cgal里面的模板类，编写很多函数类，各种纠结。一开始，我只知道有个cgal的官网，也没有找到对应的论坛，以及cgal给的例子，无从开始的感觉。
即使到现在也是无从开始的感觉，我要用cgal实现分割三维模型，而且是需要沿着画在三维模型上面的线分割。说实话，很纠结。老师说，沿着线进行欧拉操作就行了，那么怎么个具体的欧拉操作了，我现在已经看了很多次文档和example了，还翻了很多遍的论坛，也没有找到相应的信息。论坛上面说，可以用nef实现平面分割模型，稍微试了下，发现速度惨不忍睹，我使用的模型有几M大，nef基本上会卡几分钟，即使效果出来了，估计也不行吧。放弃了nef，还有一个是aabb tree，cgal里面的example可以获得平面与aabb tree相交的点，线，面。但是，例子太简单了，完全不知道获取的primitive_id是什么东西，说实话，整个关于cgal的东西，我除了找到cgal官网提供的tutorial里面的例子有价值之外，其余真的很少发现有价值的代码了。。。
cgal的安装也不简单，所以我保存了安装好的，boost 1.47和cgal 4.1的库，以后就到处使用了，我的界面用的是mfc。说起界面，也怪我自己刚开始在界面上浪费太多的时间了，其实找一个设计不错的界面例子就行了，比如tutorial的例子。但是，我也是后面发现才有这个东西的。反正自求多福吧，也不靠谁。再说我人懒真的不能怪谁，要怪真能怪自己以前不努力，人懒，人蠢，一切后果自己承担了。
   