---
title: 普遍共识语言
type: posts
date: 2023-04-09T09:22:39.364Z
author:
  name: 译者-刘征
  link: https://martinliu.cn
tags:
  - culture
  - learn
categories: 
  - foundation
type: posts
description: 应该明确的定义业务领域中的术语和概念，从而消除沟通中的歧义。
resources:
  - name: featured-image
    src: ubiquitous_language_galaxy_stable_difussion.jpeg
  - name: featured-image-preview
    src: ubiquitous_language_galaxy_stable_difussion.jpeg
---
应该明确的定义业务领域中的术语和概念，从而消除沟通中的歧义。
<!--more-->

## 难度

> 容易

## 参与者

- Team 整个团队
- ProductOwner  产品负责人
- Stakeholders 利益干系人
- Users 用户

## 定义

普遍共识语言是一种最佳实践，旨在建立一个规范、严谨和明确的语言体系，让参与软件开发过程的每个人都使用相同的语言。通常是开发团队和用户之间的共同语言，但不限于此。产品所有者和其他利益干系人也应该采用它。

它来自领域驱动设计世界。它最初来源于Eric Evans在他著作[《领域驱动设计：软件核心中的复杂性问题》](https://www.amazon.com/exec/obidos/ASIN/0321125215/domainlanguag-20)，该书发布于2003年。

## 应用场景

当业务领域非常复杂时，我们通常会发现：团队成员或用户对相同的概念有着不同的理解。

在业务领域的术语和概念方面，在沟通交流中大家缺乏一致的共识理解，这会对开发团队交付的速度和质量产生了巨大的影响，甚至可能会导致用户感到沮丧，因为他们所想的东西与最终实现的结果不同。

某些复杂领域概念的示例如下：

- 在AI模型开发领域中的 “时间旅行/Time travelling"”
- 在数据工程领域中的 “合并/Merge vs 连接/Join”

开发普遍共识语言有许多好处。它有助于：

- 更好地了解业务领域和用户。
- 消除开发过程中的歧义。
- 在开发过程中建立所有参与者之间的共同语言，特别是开发人员和用户之间。

## 如何操作

普遍共识语言的输出应该是术语和概念，以及其定义的词汇表。理想情况下，该词汇表应该可供所有参与开发过程的人阅读和评审，而不仅仅是开发人员。使用一个Git代码存储管理术语表/词汇表可能是一个理想的选择，这样我们可以方便的跟踪变更和接受建议。

不要害怕使用图示，而不光只用文字。有些概念在图示中比用简单的文字更易于解释。

可以参考下面的流程来开发普遍共识语言。

1. 从各种业务工作或实践中收集领域概念。[Event Storming 事件流程风暴](https://openpracticelibrary.com/practice/event-storming/) 是开始捕获（识别）那些所有参与者理解上有歧义的业务领域相关概念的完美方式。不要限制于只使用Event Storming的方法，其他发现实践如 [Impact Mapping](https://openpracticelibrary.com/practice/impact-mapping/) 或 [Empathy Mapping](https://openpracticelibrary.com/practice/empathy-mapping/) 也是不错的选择。
2. 制定这些概念的术语定义。
3. 与开发团队、用户、PO产品所有者等各方进行确认。征求反馈意见。
4. 迭代；)

## 社区解读

待更新。

## 延伸资源

- [《领域驱动设计：软件核心中的复杂性问题》文章](https://martinfowler.com/bliki/UbiquitousLanguage.html) 
- [Eric Evans 的著作《Domain-Driven Design: Tackling Complexity in the Heart of Software》- 图书](https://www.amazon.com/exec/obidos/ASIN/0321125215/domainlanguag-20)
- [How to develop an Ubiquitous Language - 文章](https://thedomaindrivendesign.io/developing-the-ubiquitous-language/)
- [What is DDD - Eric Evans - DDD Europe 2019 - YouTube视频](https://www.youtube.com/watch?v=pMuiVlnGqjk&t=2978s)

> 原文作者

![](https://github.com/jtudelag.png)

- 作者：Jorge Tudela
- 发布日期：JANUARY 10, 2023

> 原文链接 <https://openpracticelibrary.com/practice/ubiquitous-language/>
