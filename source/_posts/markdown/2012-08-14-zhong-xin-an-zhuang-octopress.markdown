---
layout: post
title: "重新安装octopress"
date: 2012-08-14 16:31
comments: true
categories: markdown
---

如果更换机子或者重新安装系统后，要重新获得octopress非常简单。

1.安装ruby就不说了，我喜欢用rben安装。  

2.clone已存在的库，需要上传ssh key
	git clone git@github.com:username/username.github.com.git octopress

3.切换到souce分支  
  查看远程的所有分支。
	  git branch -r
  切换分支
	  git checkout origin source

4.提交代码
	git push origin source
