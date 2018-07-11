---
title:  "界面设计之添加导航栏"
modified: 2018-07-07 
categories: 
  - 界面设计
tags:
  - 笔记  
classes: wide
header:
  overlay_image: /image/camera.jpg 
  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
#  cta_label: "More Info" 
#  cta_url: "https://unsplash.com"
  caption:
excerpt: '网页界面设计'
sidebar:
  nav: "docs"
---
 
{% include base_path %}
 
{% include toc title="目录" %}

 




**一个网页的界面中，不仅有页头、正文内容、侧边栏等，导航栏也是很重要的一个结构，它可以告知用户一个网站大致有那些界面和内容，起着为用户“导航指路”的作用。**

那么最基础的导航栏要如何添加呢？

**我们只需要打开data文件中的navigation文件，在title后输入自己想要为该栏设置的名字，若是要链接到其他的网站上，只要在url后面粘贴上想要链接的网站地址即可。**


![导航栏.png](https://upload-images.jianshu.io/upload_images/9467429-687ecf6f1d1f2ac0.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


**接下来我们需要创建一个与data，includes等同级的文件夹并命名为pages，在其中分别创建about、svg、design等markdown文件，若是有文章要放在某个栏中，则该栏的名字后面需要加上archive，如图：**

![pages.png](https://upload-images.jianshu.io/upload_images/9467429-adfd050da441d6e6.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

然后分别在相应的文件中打入代码便大功告成啦！