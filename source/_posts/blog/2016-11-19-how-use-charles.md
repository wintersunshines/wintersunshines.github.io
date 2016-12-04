---
layout: post
title: charles的基本用法
description: 学习并掌握常见的抓包工具charles的使用，学会移动端日志分析
toc: true
category: blog
tags: [charles,抓包工具，测试]
---

## 何为charles
### 简介

Charles是在Mac下常用的截取网络封包的工具，在做iOS开发时，我们为了调试与服务器端的网络通讯协议，常常需要截取网络封包来分析。Charles通过将自己设置成系统的网络访问代理服务器，使得所有的网络访问请求都通过它来完成，从而实现了网络封包的截取和分析。

Charles主要的功能包括：
支持SSL代理。可以截取分析[SSL](http://zh.wikipedia.org/wiki/%E5%AE%89%E5%85%A8%E5%A5%97%E6%8E%A5%E5%B1%82)的请求。
支持流量控制。可以模拟慢速网络以及等待时间（latency）较长的请求。
支持AJAX调试。可以自动将json或xml数据格式化，方便查看。
支持AMF调试。可以将Flash Remoting 或 Flex Remoting信息格式化，方便查看。
支持重发网络请求，方便后端调试。
支持修改网络请求参数。
支持网络请求的截获并动态修改。
检查HTML，CSS和RSS内容是否符合[W3C标准](http://validator.w3.org/)。

Charles主界面介绍
![charles](/images/Charles-main-page-introduction.jpg "主界面介绍")