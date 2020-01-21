---
title: 发布ios踩坑
date: 2020-1-21 20:13
tag: [unity,ios]
---

Strip code 问题

Xcode 端报错 
Could not produce class with ID XXX.

来自 <http://www.manongjc.com/article/59001.html> 

方案:
没有被引用到的类会被strip掉,需要加到link.xml 或者 被引用才行
 参考:http://www.manongjc.com/article/59001.html