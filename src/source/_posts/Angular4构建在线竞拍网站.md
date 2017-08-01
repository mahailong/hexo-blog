---
title: Angular4构建在线竞拍网站
date: 2017-07-20 09:05:19
tags: [code,angular]
---

既然react和vue都试了，也不差angular了
看了下官方文档，之后直接找课程开撸，
这是一个慕课网的Angular视频课程
<!--more-->

[ 源码地址 --->](https://github.com/mahailong/Ng-auction)

### 创建并推送到远程仓库

```
  npm i -g @angular/cli
  ng new Ng-auction
  cd Ng-auction
  git remote add origin git@github.com:mahailong/Ng-auction.git
  git push -u origin master
```
### 添加第三方插件

```
npm i bootstrap jquery --save 

// 安装插件的typescript类型描述文件
npm i @types/bootstrap @types/jquery --save-dev 

// .angular-cli.json文件
{
  "apps": [
    {
      "styles": [
        "../node_modules/bootstrap/dist/css/bootstrap.css"
      ],
      "scripts": [
        "../node_modules/jquery/dist/jquery.js",
        "../node_modules/bootstrap/dist/js/bootstrap.js"
      ]
    }
  ]
}

```
### angular-cli 命令
```
npm g component navbar //创建组件
```

### 请求800x300的尺寸图

[http://via.placeholder.com/800x300](http://via.placeholder.com/800x300)

### 2017/7/25

好吧   又烂尾了
这个ng4毛的依赖注入，毛的流，搞得头大，