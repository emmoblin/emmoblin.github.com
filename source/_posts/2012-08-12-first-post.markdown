---
layout: post
title: "first post"
date: 2012-08-12 23:34
comments: true
categories: test
---

随便先写一点东西，markdown语法还不熟悉

### 发现的问题
1. 即使本地加载也特别慢   
   原来是要去加载google的font，可能又要翻墙，所以特别慢。  
   注释掉：source/_include/custom/head.html中注释掉fonts.googleapis.com的link

