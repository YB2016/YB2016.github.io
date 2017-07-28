---
layout: post
title: CAD图形转JPG
date: 2017-7-28 10:03:18.000000000 +08:00
categories:
- 工作日志
tags: [教程]
status: publish
type: post
published: true
meta:
  _edit_last: '1'
  _wp_old_slug: hello-world
  views: '1'
author:
  login: slayer
  email: wy8812@gmail.com
  display_name: slayer
  first_name: ''
  last_name: ''
---

<!-- more -->

对于AutoCAD的初学者来说，初步掌握了一些基本的操作技能，可以画一些简单的图形，就已经迈出了第一步。逐渐深入学习后，慢慢的就会出现很多问题，我今天要聊的这个问题相信大家都会遇到：一个CAD的图形怎样才能转成一张图片，而且这张图片的分辨率要高，图片上的内容不失真。

好的，直接切入正题。

1、打开AutoCAD，找到你需要转成JPG的CAD图形内容。

2、Ctrl+p或者“文件—打印”，调出打印文件的窗口。



3、在打印窗口中找到“打印机/绘图仪”，点开下拉菜单，找到DWG To PDF.pc3。注：我手头两台电脑分别安装了AutoCAD2004、2008和2016,2004版本的没有这个选项，其余的两个都有。

4、选好DWG To PDF.pc3之后，在下面的“打印范围”中选“窗口”，这时，就会弹回到CAD的主窗口，光标变成选择状态，框选你需要转换的内容，又跳回打印窗口，然后点击右下角的箭头，点选图形的方向，调整合适后，点击“确定”。选择合适的路径、给定保存文件名称，然后保存这个PDF文件。

5、我们打开刚才保存的路径，可以看到有个PDF文件出现。单击右键，“打开方式—Photoshop打开”。

6、使用Photoshop打开后，图形界面呈虚化的像素格状态，没关系，继续下一步。

7、点击“文件—存储为”，调出另存为的窗口，给定文件名称，然后在“保存类型”一栏中，点选“JPEG(.JPG,.JPEG,.JPE)”.

8、这样，就生成了一个JPG文件，打开后可以通过放大缩小来检验图片的质量。







