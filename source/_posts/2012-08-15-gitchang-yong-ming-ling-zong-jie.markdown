---
layout: post
title: "git常用命令总结"
date: 2012-08-15 11:58
comments: true
categories: git
---

我只记录一些我的常用命令，一些不常用的即使写了过一段时间也会忘掉的。实在要用直接help一下就行。

### gitconfig ###

```
[color]
	status = true
	branch = auto
	diff = auto
	ui = auto

[alias]
	st = status
	co = checkout
	ci = commit -a
	l = log --graph

[user]
	name = username
	email = youremail
```

### 备忘 ###
`git log --all`

  git log只会显示HEAD及其祖先的log，要产看全部使用--all

`git stash`
  
  非常有用的命令，把当前work目录做临时保存，并revert到HEAD。
  使用git stash apply进行恢复。
  
  
  
[git权威指南作者blog](http://www.worldhello.net/)