---
title:  "界面设计之字体的更换与排列"
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

 

**在我们搭建一个网站之后，常常需要从各方面考虑用户的使用感受，比如界面的颜色搭配，字体的大小，清晰度是否足以使用户看清写的是什么。而其中，我们要如何对字体进行更换呢？**

在平面设计之更换背景颜色那一篇文章中，我们有提到新建一个aqua后加自己名字的文件夹。我们打开那个文件夹，找到$masthead-link-color-hover  : mix(#000, $primary-color, 25%) !default;这一行代码，将其删去并更换为以下代码：

![更换中文字型.png](https://upload-images.jianshu.io/upload_images/9467429-f2d3c3dd52e23ae0.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


完成这一步之后，我们再找到serif和sans-serif这两行代码，将其更换为以下代码：
![更换字体.png](https://upload-images.jianshu.io/upload_images/9467429-cd0a7600a1df0ccc.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


然后我们便成功将字体更换了。


而我们只需要在markdown文章的头部添加一行“classes: wide”便可以使文章的内容向右延展。


![文字排列.png](https://upload-images.jianshu.io/upload_images/9467429-860d680a26d8fb0e.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
