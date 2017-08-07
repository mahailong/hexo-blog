---
title: Ionic仿Cnode社区App
date: 2017-08-02 14:41:10
tags: [code,ionic]
---

[ 项目预览 --->](https://mahailong.github.io/Ionic-Cnode/www/)
 
[ 项目源码 --->](https://github.com/mahailong/Ionic-Cnode)
 
### 项目简介
 
这是一个基于ionic的cnode客户端

<!--more-->
 
感谢[cnodejs论坛](https://cnodejs.org/)官方提供的api


## 页面
- home:首页列表，加入侧边栏及上拉加载功能。
- article:主题详情，登陆后能够收藏，评论和点赞。
- message:消息提醒，能查看消息详情和清空所有未读消息
- user:个人主页，包括最近参与，回复，以及收藏的主题
- publish:发表主题，react-draft-wysiwyg作为编辑器，发布成功后能跳转到相应主题页面
- about:关于页面，APP介绍
- login:登录页面，登录后会把accesstoken存于localStore


## 运行项目
```
  git clone https://github.com/mahailong/Ionic-Cnode.git
  cd React-Cnode
  npm install
  npm start
```
