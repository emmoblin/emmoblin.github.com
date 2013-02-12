---
layout: post
title: "emacs markdown-mode"
date: 2012-08-15 12:38
comments: true
categories: [emacs,markdown]
---

#### 锚标签 C-c C-a ####
`C-c C-a l` 超链接  
`C-c C-a r` 参考链接 text 参考链接放到文件最后 [label]: markdown.html  
`C-c C-a w` wiki链接 [[wikilink]]  

#### 常用命令 C-c C-c  ####
`C-c C-c m` 在另一个Buffer显示输出  
`C-c C-c p` 在浏览器中预览输出  
`C-c C-c e` 输出html文件到相同前缀的.html文件 eg:basename.html  
`C-c C-c v` 输出并且在浏览器中查看  
`C-c C-c c` 检查是否有未定义的链接  

#### 插入图片 C-c C-i  ####
`C-c C-i i` 插入一张图片

#### 物理样式 C-c C-p  ####
`C-c C-p b` 将选中的文字加粗 bold **bold** 如果为选中则插入 ****  
`C-c C-p f` 将选中的文字设置成等宽字体 <code>fixed width text</code>  
`C-c C-p i` 将选中的文字设置成斜体 italic*italic*  

#### 逻辑样式 C-c C-s ####
`C-c C-s b` 设置引用 > backquoted  
`C-c C-s p` 预格式，在之前插入4个空格默认 `<pre>pre text</pre>`  
`C-c C-s c` 插入代码块 <code>code here</code>  
`C-c C-s e` 强调 emphasis *emphasis*  
`C-c C-s s` 加强 strong **strong**  

#### 标题章节 C-c C-t ####
`C-c C-t n` 插入标题 1-6  
`C-c C-t t` 插入一个title  
`C-c C-t s` 插入一个section  
`C-c -` 插入一条分割线  

* * * * *
#### 导航 ####
`TAB` 折叠或者展开标题  
`C-M-n & C-M-p` 在上下可见的标题中前后移动  
`C-M-f & C-M-b` 在同一级的标题中前后移动  
`C-M-u` 回到上一级标题

## 参考 ##
[Emacs Markdown Mode](http://jblevins.org/projects/markdown-mode/)

