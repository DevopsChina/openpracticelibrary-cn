---
title: Ubiquitous 语言
type: posts
date: 2023-04-09T09:22:39.364Z
author:
  name: 作者：jtudelag， 译者 刘征
tags:
  - culture
  - learn
categories: 
  - foundation
type: posts
description: 明确定义业务领域的术语和概念，使其没有歧义。
resources:
  - name: featured-image
    src: featured-image.png
---
明确定义业务领域的术语和概念，使其没有歧义。
<!--more-->

## 什么是 Ubiquitous Language？

Ubiquitous Language是一种最佳实践，旨在建立一个规范、严谨和明确的语言，让参与软件开发过程的每个人都使用相同的语言。通常是开发团队和用户之间的共同语言，但不限于此。产品所有者和其他利益相关者也应该采用它。

它来自领域驱动设计世界。它最初是由Eric Evans在他自己的书[《领域驱动设计：软件核心中的复杂性问题》](https://www.amazon.com/exec/obidos/ASIN/0321125215/domainlanguag-20)中于2003年首次介绍的。

## 为什么要使用Ubiquitous Language？

当业务领域非常复杂时，通常会发现团队成员或用户对相同概念有不同的理解。

缺乏共同的理解对开发团队交付的速度和质量产生了深刻的影响，也可能会导致用户感到沮丧，因为他们所想的与最终实现的不同。

一些复杂领域概念的示例：

- 在AI模型开发领域中的“时间旅行”
- 在数据工程领域中的“合并 vs 连接”

开发Ubiquitous Language有许多好处。它有助于：

- 更好地了解业务领域和用户。
- 消除开发过程中的歧义。
- 在开发过程中建立所有参与者之间的共同语言，特别是开发人员和用户之间。

## 如何使用Ubiquitous Language？

Ubiquitous Language的输出应该是术语和概念以及其定义的词汇表。理想情况下，该词汇表应该可供所有参与开发过程的人阅读和审核，而不仅仅是开发人员。一个Git存储库可以跟踪和建议更改，可能是一个理想的地方。

不要害怕画图而不是写字。有些概念在图示中比用简单的文字更易于解释。

为了开始开发Ubiquitous Language：

1. 从其他实践中收集领域概念。Event Storming是开始捕捉与业务领域相关但不是所有Event Storming参与者同样理解的概念的完美实践。不要限制自己只使用Event Storming，其他发现实践如Impact Mapping或Empathy Mapping也是不错的选择。
2. 为这些概念制定定义。
3. 与开发团队、用户、产品所有者等进行验证。征求反馈意见。
4. 迭代；)

## 详见Ubiquitous Language视频

《B站视频转载中》


## 参考资源

- [《领域驱动设计：软件核心中的复杂性问题》文章](https://martinfowler.com/bliki/UbiquitousLanguage.html) 
- ['Eric Evans book: "Domain-Driven Design: Tackling Complexity in the Heart of Software" - 图书](https://www.amazon.com/exec/obidos/ASIN/0321125215/domainlanguag-20)
- [How to develop an Ubiquitous Language - 文章](https://thedomaindrivendesign.io/developing-the-ubiquitous-language/)
- [What is DDD - Eric Evans - DDD Europe 2019 - 视频](https://www.youtube.com/watch?v=pMuiVlnGqjk&t=2978s)

## 难度

容易

## 参与者

  - Team 整个团队
  - ProductOwner  产品负责人
  - Stakeholders 利益干系人
  - Users 用户


## 原文链接

<https://openpracticelibrary.com/practice/ubiquitous-language/>
