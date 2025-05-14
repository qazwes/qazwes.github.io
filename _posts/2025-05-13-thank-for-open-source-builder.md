---
layout:     post
title:      Acknowledgment 致谢
subtitle:   thank for the work of qiubaiying
date:       2025-05-13
author:     noname
header-img: img/post-thank.jpg
catalog: true
tags:
    - 个人博客
    - 开源框架
    - jekyll
    - github pages
---

## 前言
无聊了好久  

突然想干点什么  

于是做博客  
## 正文
首先上github挑选称心的厨具，桀桀桀，轻松就找到了宝藏。[这个项目](http://https://github.com/qiubaiying/qiubaiying.github.io?tab=readme-ov-file)正是我想要的啊。git clone,启动！出现报错`fatal: 无法访问 'https://github.com/xxxxx/xxxxx.github.io.git/'：Recv failure: 连接被对方重置`多半是因为开了梯子，当然也可能是沟曹的校园网。这时不妨使用这个命令`git config --global http.proxy http://127.0.0.1:7890`设置一下代理，然后`git config --global -l`看一下代理设置成功了没。  

哎，git怎么这么坏啊！尝试将他人的项目clone入自己的库无果。拼尽全力选择放弃，老实按哥们教程走。我有技术吗？如有！大伙记得注意改一下远程连接。首先`git remote -v`看看当前库连接到那里的。首先的首先`cd the path of your git clone`。然后`git remote remove origin`，再`git remote add origin your remote url`。不然的话柏荧老哥就得吃n记洛阳铲了。
## 后记
trae是真好用啊
## 后记的后记
图片名称不能用数字，用字母没问题。用数字会导致图片无法正常显示，目前不知道为什么。
