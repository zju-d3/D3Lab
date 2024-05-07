---
title: AutoSpark：利用感性工学和生成式 AI 来支持汽车外观设计
authors:
  - 陈柳青
  - jqz
  - zyx
  - wqy
  - xdw

date: 2024-05-01
weight: 10

math: true
highlight: true

tags:
  - LLMs
  - Generative AI

# Featured image

# To use, add an image named `featured.jpg/png` to your page's folder

image:
caption: ""
focal_point: ""
preview_only: false
---

Product Appearance Design Ideation, Creativity Support Tool, Generative AI

<!--more-->

## 项目简介

快速创建符合消费者情感需求的新颖的汽车外观设计是一项具有挑战的任务。最近广受欢迎的文生图模型以其出色的图像生成能力在为设计师提供灵感方面表现出极大的潜力。然而，在实际应用中，设计师仍然会面临一些问题，包括设计师与 AI 对于情感需求的定义和理解存在偏差，设计意图难以表达，模型的生成过程和生成结果难以理解和控制。在这项工作中，我们提出了一个集成了感性工学和生成式人工智能的智能交互系统，AutoSpark。它帮助设计师创造满足消费者情感需求的汽车外观设计，通过图像-图像和文本-图像的比较来迭代设计，并通过设计思维地图来管理创意过程。

我们推出了 AutoSpark，这是一个集成了感性工程学和生成式人工智能的互动系统，为设计师创造满足情感需求的汽车外观设计提供创意支持。AutoSpark 采用由生成式人工智能和语义网络驱动的感性工程引擎来支持设计师进行情感词发散，情感词到设计特征的转译以及设计特征提取，从而帮助设计师实现情感需求对齐、设计意图的快速表达，并利用大语言模型根据提取出的设计特征进行提示词生成，帮助设计师快速利用文生图模型创建汽车图像。为了促进设计师对生成结果的理解和迭代，AutoSpark 利用 CLIP 模型辅助设计师对生成图像进行细粒度的相似性比较，利用 patch-inversion 算法可视化文本提示词和生成图像之间的相关性。AutoSpark 还在界面中提供了一个设计思维导图来帮助设计师高效管理设计过程。我们的用户研究表明，与基线系统相比，AutoSpark 能够有效地帮助设计师生成更符合消费者情感需求并且质量更高的汽车设计图像，同时也增强了设计师在人机共创过程中的体验。
