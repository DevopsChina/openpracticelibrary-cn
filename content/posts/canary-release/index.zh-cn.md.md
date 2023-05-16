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
description: 让少量真实用户先触达新版本。
resources:
  - name: featured-image
    src: canary-release.jpg
  - name: featured-image-preview
    src: canary-release-h.jpg
---
让少量真实用户先触达新版本。
<!--more-->

## 难度

> 中等

## 参与者

- 两人以上

## 定义

这是一种在软件开发过程中的，让产品的少量真实用户先触达到新版本的持续交付方式。产品团队应当实时监控发布对系统可能会造成的性能回归，或者性能方面的问题，以及任何其他的不良影响。一旦发现到了任何问题，就可以比较轻松地将用户流量切换回工作正常的旧版本。

这个术语来自于煤矿，矿工为了尽早的发现有毒气体，从而将一种关在笼子中的鸟带入井下。在有害气体对矿工造成生命威胁之前，小鸟便会提前丧命。正如矿井里的金丝雀，这种发布方式的目的是：为避免出现更大的问题，提供了一种早期的预警机制。

## 使用场景

这是一种循环反馈的做法，这使得团队能从真实的生产环境中，实时的获取产品更改的反馈。它使[持续交付](https://openpracticelibrary.com/practice/continuous-delivery/)成为可能。

## 实现方式

金丝雀发布与[A/B 测试](https://openpracticelibrary.com/practice/split-testing-a-b-testing/)相似，只让一部分用户先触达新版本。但是与[A/B 测试](https://openpracticelibrary.com/practice/split-testing-a-b-testing/)不同的是，新特性通常是一个全新的特性，而不只是对已有旧特性的微调。两者的目的也是不同的，[A/B 测试](https://openpracticelibrary.com/practice/split-testing-a-b-testing/)是为了取得业务产出（如：营业额、订单数量等）而改进产品表现，而金丝雀发布则完全侧重于技术上的性能。

金丝雀发布与[暗发布](https://openpracticelibrary.com/practice/dark-launches/)也有相似，两者都只对一部分用户发布新版本。[暗发布](https://openpracticelibrary.com/practice/dark-launches/)关注于理解用户对新特性的反应以及使用情况，而金丝雀发布真正的关注于变更的整个产品，或者某个独立特性在技术方面的性能（是否可以从架构中隔离使用）。

‘功能开关’也是一种有意义的方式，它可以让我们在已经投产的系统中实施金丝雀发布。

> 相关实践：

- [功能开关](https://openpracticelibrary.com/practice/feature-toggles/)
- [暗发布](https://openpracticelibrary.com/practice/dark-launches/)
- [蓝绿部署](https://openpracticelibrary.com/practice/blue-green-deployments/)
- [持续交付](https://openpracticelibrary.com/practice/continuous-delivery/)

## 延伸资源

- 文章 [Blue-green Deployments, A/B Testing, and Canary Releases](http://blog.christianposta.com/deploy/blue-green-deployments-a-b-testing-and-canary-releases/) by Christian Posta
- 文章 [Canary Release](https://martinfowler.com/bliki/CanaryRelease.html) by Martin Fowler
- 视频 [What is Canary Testing? | Implementing A Full CI/CD Pipeline](https://www.youtube.com/watch?v=FT2O-qLj9Hc&ab_channel=LinuxAcademy) by Linux Academy

{{< bilibili BV1vo4y1x7Lo >}}

> 原文作者

![](https://avatars.githubusercontent.com/u/23172281?v=4)

- Val Yonchev
- PUBLISHED DECEMBER 18, 2018

> 原文链接：<https://openpracticelibrary.com/practice/canary-release/>

Image credit: Photo by [Julia Craice](https://unsplash.com/photos/o0S-0Pa4F2M) on Unsplash
