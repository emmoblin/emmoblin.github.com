---
layout: post
title: "octopress添加分类栏"
date: 2012-08-14 23:09
comments: true
categories: octopress
---

参考：[octopress-tagcloud][link1]

[link1]: https://github.com/tokkonopapa/octopress-tagcloud "octopress-tagcloud"
	
*  下载并copy到对应目录

		├─ plugins/
	    │  └── tag_cloud.rb
	    └─ source/
	       └─ _includes/
    	      └─ custom/
        	     └─ asides/
            	    ├─ category_list.html
                	└─ tag_cloud.html


* 在_config.yml中的default_asides中添加

		custom/asides/category_list.html
		custom/asides/tag_cloud.html
	
