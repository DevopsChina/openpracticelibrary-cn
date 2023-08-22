---
title: 一切皆代码
subtitle: 一切都可以写成代码，包括配置、基础设施和流水线
date: 2023-08-08
authors:
  name: 译者-王子建
  link: https://github.com/actini
tags:
  - methods
categories:
  - foundation
description: 在程序员的眼里，整个宇宙也不过是一行行代码，就像是现实版的 Metrix
resources:
  - name: featured-image
    src: everything-as-code.jpeg
  - name: featured-image-preview
    src: everything-as-code-preview.png
---
## 定义

  一切皆代码的实践其实就是把系统的所有组成部分都当成代码。比如用代码将配置保存在 Git 或者 SVN 仓库中。全方位地将配置代码化（包括功能开关、裸机服务器、操作系统、构建配置、应用属性和部署配置等）意味着所有的配置都可以被追踪，只需点击鼠标就能够重新创建这些配置。

  一切皆代码也包括系统设计代码化。在以前 IT 的工作中，往往需要专业的技能、硬件和线缆才能部署基础设施，整个系统非常脆弱，尤其是在部署的人辞职之后，几乎不进行系统的更新或改动。随着云计划和云原生应用时代的到来，建设虚拟化的基础设施变得简单又便宜。采用代码记录虚拟化的环境配置，我们可以很方便地管理环境的生命周期，并且随时根据需要重建整个环境。

## 概念

  1. **可追溯性** - 用 `git` 保存应用配置意味着能够追溯配置变更的作者和原因，这些配置随时都能够被部署、回滚，并且能够追溯到修改的人。

  1. **可重复性** - 在现代应用开发中，从一个云平台换到另一个应该是很容易的事情，而选择云平台也应该货比三家找到性价比最好的那家。如果你能把所有的内容都保存成代码，整个系统就可以分分钟部署到不同的云平台上。

  1. **测试安全** - 基础设施和代码可以部署、验证并推广到生产环境中，并有信心保证其按预期运行。

  1. **故障恢复** - 无需再为服务器配置管理犯难，就算服务器需要打补丁或者突然挂掉也没关系，只需按照保存的配置代码重新创建它即可。

  2. **基本共识** - 多个团队遵循“一切皆代码”的原则来共同开发产品，有助于增加开发人员和运营人员之间的共识，因为他们都使用代码来描述该产品的状态，使用相同的工作方式来完成工作。

## 实践

  * [Martin Fowler](https://martinfowler.com/bliki/InfrastructureAsCode.html) 的基础设施即代码实践。

  * [Terraform](https://www.terraform.io/) 是一个基础设施即代码的平台，兼容 AWS、Azure、Google Cloud 和其他云平台，以及私有的数据中心。Terraform 支持管理各种各样的组件，比如服务器、数据库、负载均衡、缓存、防火墙配置、SSL 证书、消息队列、监控、网络配置、路由规则等等。

  * [Ansible](https://www.ansible.com/) 是一个由开源界的泰山北斗 Red Hat 开发的基础设施自动化工具。

## 延伸资源

* [Martin Fowler](https://martinfowler.com/bliki/InfrastructureAsCode.html)
* [Ansible](https://www.ansible.com/)
* [Infrastructure-as-code](https://www.youtube.com/watch?v=E2KOF3AdNy0&list=PLkg9jnMh6bhd0avDugIM81BU9VkBEaMMz&index=10&t=0s)

> 原文作者

- Marcos Entenza
- Donal Spring
- PUBLISHED AUGUST 15, 2018

> 原文连接：https://openpracticelibrary.com/practice/everything-as-code/
---
