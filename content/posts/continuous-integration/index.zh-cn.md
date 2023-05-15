---
title: 持续集成
type: posts
date: 2023-05-23T20:39:25.365+08:00
author:
  name: 译者-刘世超
  link: https://openpracticelibrary.devopschina.org/
tags:
  - methods
categories: 
  - foundation
description: 持续集成，频繁地提交小的变更，而不是偶尔提交大的变更
resources:
  - name: featured-image
    src: continuous-integration.png
  - name: featured-image-preview
    src: continuous-integration.png
---
持续集成，频繁地提交小的变更，而不是偶尔提交大的变更

## 难度

> 中等

## 参与者

- 团队成员

## 定义

采用持续集成（CI）时，开发人员频繁地提交小的变更，而不是偶尔提交大的变更。当另一名开发人员接受这些变更时，需要运行构建和自动化测试，以确保代码可以按预期运行。这个操作是经常性的，每天自动化运行多次，以确保代码库可以持续集成。

这些构建和测试通常运行在自动化服务器上，比如 [Jenkins](https://jenkins.io/) 或 [Travis](https://travis-ci.org/)。

## 使用场景

- 自动化测试减少繁琐的工作并提高软件质量。
- 小而频繁的代码提交减少集成问题。
- 快速的反馈循环降低新人入门门槛。
- 这很有趣！以小增量的方式交付可运行软件比等待某人手动测试庞大的代码变更更令人愉快。

## 延伸资源

- 网站: <https://jenkins.io/doc/> Jenkins 文档
- 网站: <https://docs.gitlab.com/ee/ci/> GitLab CI/CD 文档

> 原文作者

- tdbeattie
- rdebeasi
- mtakane
- springdo
- Zenigata
- rmarting
- itblaked
- PUBLISHED AUGUST 10, 2018

> 原文链接：<https://openpracticelibrary.com/practice/continuous-integration/>
