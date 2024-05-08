---
title: AskNatureNet：基于仿生设计知识的发散思维工具
authors:
  - 陈柳青
  - czb
  - jzj

date: 2024-05-02
weight: 10

math: true
highlight: true

tags:
  - VR
  - LLMs

# Featured image

# To use, add an image named `featured.jpg/png` to your page's folder

image:
caption: ""
focal_point: ""
preview_only: false
---

Bio-inspired design， Semantic network， Divergent thinking， Design creativity， Design ideation

<!--more-->

## 项目简介

发散性思维是在设计中探索多种可能的解决方案的过程，是在设计的早期阶段打破僵化、拓展设计思维的关键。类比设计促进发散思维，通过研究解决类似问题的解决方案，并利用这些知识在新的和不熟悉的情况下进行推理和解决问题。仿生设计是类比设计的一种形式，其知识为类比提供了多样化的来源，使其成为发散思维的潜在来源。在这项工作中，我们提出了一种新的方法，从编码、检索和映射三个后续阶段支持发散思维。具体地说，通过使用大语言模型(LLM)从仿生设计知识库中提取关键信息，将生物知识以三重形式编码。创建的三元组在语义网络中实现，以促进双向检索模式：问题驱动和解决方案驱动，以及针对发散思维的映射。该映射算法遵循发散思维的范式，分三步基于属性计算语义网络中节点间的语义相似度。该方法被实现为 AskNatureNet 1 工具，它通过在可视化的交互语义网络中检索和映射知识来支持发散思维。一个评估 AskNatureNet 有效性的构思案例研究表明，我们的工具能够有效地支持发散思维。
