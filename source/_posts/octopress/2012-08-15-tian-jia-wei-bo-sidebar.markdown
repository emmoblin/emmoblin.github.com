---
layout: post
title: "添加微博sidebar"
date: 2012-08-15 00:50
comments: true
categories: octopress
---

使用[微博秀](http://weibo.com/tool/weiboshow)直接生成对应的代码，然后写到custom/asides/weibo.html中。

```html
<section>
<h1>新浪微博</h1>
<ul id="weibo">
<li>
<iframe width="100%" height="550" class="share_self"  frameborder="0" scrolling="no" 
src="http://widget.weibo.com/weiboshow/index.php?
language=&
width=0&
height=550&
fansRow=2&
ptype=1&
speed=0&
skin=5&
isTitle=1&
noborder=1&
isWeibo=1&
isFans=0&
uid=1905507693&
verifier=e659651a&
dpc=1"></iframe>
</li>
</ul>
</section>
```

然后在_config.yml中添加default_asides中：
		custom/asides/weibo.html
	
参考：<http://programus.github.com/blog/2012/03/03/add-weibo-sidebar-into-octopress/>

