---
title: 金丝雀发布
type: posts
date: 2023-05-02T12:58:00
author:
  name: 译者-隋悦豪
  link: https://hi.amao.run
tags:
  - learn
categories: 
  - delivery
type: posts
description: 让少量真实用户接触到新版本。
resources:
  - name: featured-image
    src: canary-release.jpg
  - name: featured-image-preview
    src: canary-release.jpg
---
让少量真实用户接触到新版本。
<!--more-->

## 难度

> 中等

## 参与者

- 两人以上

## 这是什么？

在软件开发中，这是使产品的少量真实用户接触到产品新版本的一种持续交付的形式。产品团队应当监控退步、性能问题和其他不利影响。如果发现问题，可以很容易地将用户移回工作的旧版本。

这个术语来自于在煤矿中，为了尽早发现气体泄漏而使用的一种关在笼子中的鸟。在这些气体对矿工造成生命威胁之前便会使得小鸟丧命。正如矿井里的金丝雀，这种发布方式为避免更大的问题出现提供了一种早期预警机制。

## 为了什么？

这是一种循环反馈的做法，这使得团队能从现实情况中为他们的更改得到实时反馈。这启用了[持续交付](https://openpracticelibrary.com/practice/continuous-delivery/)。

## 相关实践。

金丝雀发布与[A/B 测试](https://openpracticelibrary.com/practice/split-testing-a-b-testing/)相似，只让一部分用户接触新版本。但是与[A/B 测试](https://openpracticelibrary.com/practice/split-testing-a-b-testing/)不同的是，新特性通常是一个全新的特性而不只是对现用特性的小调整。两者的目的也是不同的，[A/B 测试](https://openpracticelibrary.com/practice/split-testing-a-b-testing/)是为了获得商业成果而提升产品性能，而金丝雀发布则完全侧重于技术上的性能。

金丝雀发布与[暗部署](https://openpracticelibrary.com/practice/dark-launches/)相似，两者都只对一部分用户发布新版本。[暗部署](https://openpracticelibrary.com/practice/dark-launches/)关注于理解用户对新特性的反应以及使用情况，而金丝雀发布真正的关注于更改的产品的技术性能或者独立的特性（是否可以从架构中隔离使用）。

功能转换是一种有用的方式，它允许在现有产品中实施Canary发布。

### 功能转换

[暗部署](https://openpracticelibrary.com/practice/dark-launches/)

[蓝绿部署](https://openpracticelibrary.com/practice/blue-green-deployments/)

[持续交付](https://openpracticelibrary.com/practice/continuous-delivery/)

## 延伸资源

[Blue-green Deployments, A/B Testing, and Canary Releases](http://blog.christianposta.com/deploy/blue-green-deployments-a-b-testing-and-canary-releases/) by Christian Posta

[Canary Release](https://martinfowler.com/bliki/CanaryRelease.html) by Martin Fowler

Image credit: Photo by [Julia Craice](https://unsplash.com/photos/o0S-0Pa4F2M) on Unsplash

> 原文作者

![](https://avatars.githubusercontent.com/u/23172281?v=4)

- Val Yonchev
- PUBLISHED DECEMBER 18, 2018

> 原文链接：<https://openpracticelibrary.com/practice/canary-release/>
