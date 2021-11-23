<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [jike_webpack](#jike_webpack)
  - [章节内容](#%E7%AB%A0%E8%8A%82%E5%86%85%E5%AE%B9)
  - [介绍](#%E4%BB%8B%E7%BB%8D)
  - [需求](#%E9%9C%80%E6%B1%82)
  - [技术预研](#%E6%8A%80%E6%9C%AF%E9%A2%84%E7%A0%94)
  - [项目开发](#%E9%A1%B9%E7%9B%AE%E5%BC%80%E5%8F%91)
  - [极客时间网站开发](#%E6%9E%81%E5%AE%A2%E6%97%B6%E9%97%B4%E7%BD%91%E7%AB%99%E5%BC%80%E5%8F%91)
  - [APP下载页](#app%E4%B8%8B%E8%BD%BD%E9%A1%B5)
    - [模板字符串](#%E6%A8%A1%E6%9D%BF%E5%AD%97%E7%AC%A6%E4%B8%B2)
    - [启动rpc后端服务（前端模拟）](#%E5%90%AF%E5%8A%A8rpc%E5%90%8E%E7%AB%AF%E6%9C%8D%E5%8A%A1%E5%89%8D%E7%AB%AF%E6%A8%A1%E6%8B%9F)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# jike_webpack

## 章节内容

    1.项目介绍
    2.技术预研
    3.项目开发
    4.性能调优
    5.框架和工程化

## 介绍

1.Chrome V8引擎
2.事件驱动，非阻塞式I/O

## 需求

    极客时间网站
    1.列表页
        打通前后台
        服务端渲染
    2.详情页
        网页路由
        异步加载
    3.播放器
        API服务器

## 技术预研

    1.石头剪刀布游戏
    2.commonjs
    3.nodejs 内置模块
    4.异步
        非阻塞I/O:
            在接收系统输入输出的阶段过程中，也可以接受其他的输入输出
    5.promise，async/await
    6.http服务器
    7.

## 项目开发

    1.向前提供HTTP服务
    2.向后进行RPC通信

## 极客时间网站开发

    1.详情页
    2.播放页
    3.列表页

## APP下载页

    1.node-mon
    2.nodemon index.js

### 模板字符串

### 启动rpc后端服务（前端模拟）

    1.cd /Users/lipeng/Desktop/geek/geek-nodejs-master/section30/detail-server
    node start.js
