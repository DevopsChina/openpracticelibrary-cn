---
title: GitOps
subtitle: 没有在 Git 仓库里的，都是假的。
type: posts
date: 2023-05-10
author:
  name: 译者-王子建
  link: https://github.com/actini
tags:
  - methods
categories:
  - foundation
description: 习惯了用 Git？那就用 Git 来做所有的事情吧！
resources:
  - name: featured-image
    src: gitops.png
  - name: featured-image-preview
    src: gitops-preview.png
---
## 定义

  GitOps 是一种通过 Git 操作来管理开发、发布工作流程的模式，其概念相当直观：

  * [一切皆代码:](https://openpracticelibrary.cn/practice/everything-as-code/) Git 代码库永远反映了系统最真实的状态

  * 部署、测试和回滚都通过 Git 操作来管理

  * 没有任何手动的部署/变更：如果你想做修改，那就用 Git 来实现，可以提交一个 Git commit 或者发起一个 pull request。

  GitOps 提供了简洁的操作、更佳的开发体验和更好的系统观测性。当前最流行的 GitOps 工具当属 ArgoCD 和 Flux 莫属，随着 GitOps 越来越流行，与这些方法和工具相关的最佳实践也在越来越多。

## 概念

  其实，GitOps 一开始是用来解决“系统即代码”的问题，它摒弃了直接对系统进行操作，选择了和 Git 仓库进行交互的方式。然而，GitOps 不仅能够为企业提供“一切皆代码”的工作方式，更能帮助企业推动 DevOps **文化**和**实践**。

  GitOps 的好处：

  * 强制使用声明性描述内容和版本控制。即使开发人员已经能够很熟练地使用 Git 来管理应用代码，但 GitOps 意味着除了源代码之外，还需要存储其他和应用相关的内容。只要不在 Git 代码库里的，都是假的！

  * 减少应用代码和基础设施代码的区别。

  * 推动 DevOps 文化和实践的应用。GitOps 提供的声明式自动化部署能够优化 lead time 的时间。

  * 提高可追溯性。借助 Git 代码库，没有任何变更能够瞒天过海不着痕迹。

  * 提高安全性。如果应用的安全规范以 manifest 文件的形式保存在 Git 仓库，那你可以放一百个心因为 GitOps 会将他们都部署上去。另外，Git 作为单一可信源（Single Source of Truth）也发挥了巨大的安全优势，因为 Git 里记录了所有的变更。

  * 最大程度地减少配置不一致的问题。如果 Git 仓库中记录的内容和系统实际的状态有差别，GitOps 工具会发出告警甚至还能尝试回滚系统中的变更（直到与 Git 仓库中记录的内容相同）。

  * 在整个软件生命周期中实现可读性和可观测性。只需要查看 Git 仓库中的内容就能轻松地知晓系统地运行状态。

  * 减少故障恢复时间（Mean Time To Recovery）。只需要按照某一个 Git commit 来部署，就能够将系统回滚到对应的历史版本。

  如上所述，GitOps 方法并不只是围绕着 Git commit 和 pull request 工作，它还能够提高产品的可观测行和团队的透明度。采用 GitOps 方法来开展和扩展 IT 团队的交付能力可以极大地提高团队面对市场或重大事件的响应能力。GitOps 能够提高反复搭建环境、部署开发工具的工作体验，也能在灵活变化的团队中提高应用迁移和开发的产出效率。

## 实践

  在云原生的世界里，持续交付意味着每个 Git commit 都可以在无人介入的情况下自动地部署到生产环境，因此 GitOps 简直就是为持续交付而量身定做的。

  在团队中，大家应该对 GitOps 实践的内容有所共识，比如定义 Git 仓库的文件结构，哪个配置文件应该放在哪里，然后再利用正确的 GitOps 工具来实现需求。当然，Git 仓库的设置有很多种方式，举个例子，在这个 CI/CD 流水线的流程简图中有两个 Git 仓库，一个用来保存配置文件和另一个用来保存源代码：

  ![GitOps Approach with Helm and Argo CD](/images/helm-argo-cd-page-1.png)

  #### ***Open Practice Library 项目正在使用 GitOps！***

  Open Practice Library 项目有很多微服务和前端应用，这些代码散布在不同[Git 仓库](https://github.com/openpracticelibrary/opl-cd)里。在这些代码库里，服务被定义为 manifest 文件，并且所有 manifest 文件的变更都会通过 GitHub Actions 集成到 Open Practice Library 不同的发布版本中。整个项目通过 ArgoCD 来自动地将 manifest 文件的变更部署到 Red Hat OpenShift Container Platform 中运行的应用中。

## 延伸资源

  - [Ubiquitous Journey - an implementation of GitOps](https://github.com/rht-labs/ubiquitous-journey)
  - [Red Hat OpenShift GitOps](https://www.openshift.com/blog/announcing-openshift-gitops)
  - [Argo CD - a popular GitOps tool](https://argoproj.github.io/argo-cd/)
  - [What is GitOps](https://www.weave.works/technologies/gitops/)

> 原文作者

- [Cansu Kavili](https://github.com/ckavili)
- PUBLISHED APRIL 20, 2021

> 原文连接：https://openpracticelibrary.com/practice/gitops/
---
