---
title: UI元素语义分组研究
authors:
  - 陈柳青
  - xsh
  - cyn
  - syx

date: 2024-05-01
weight: 10

math: true
highlight: true

tags:
  - UI

# Featured image

# To use, add an image named `featured.jpg/png` to your page's folder

image:
caption: ""
focal_point: ""
preview_only: false
---

UI element grouping, UI object detection, UI-related software application, Transformer

<!--more-->

## 项目简介

在现代软件工程中，用户界面（UI）元素的有效组织和识别是增强应用程序交互性和功能性的关键。尽管现有的研究提出了多种 UI 元素分组的方法，但这些方法往往针对特定的软件工程任务，如 UI 测试和代码生成，而且这些分组在外观和功能上的多样性限制了其普遍适用性。

本文提出了一种新的 UI 语义组件分组方法，旨在通过深度学习技术提高 UI 元素分组的普适性和效率。该方法使用改进的 Deformable-DETR 模型，结合 UI 元素颜色表示和组分布学习，从而能够识别出具有相似语义的 UI 元素组。此外，所提出的 UISCGD 模型不仅提升了分组的检测性能，还能支持多种 UI 相关的软件工程任务，如感知组检索、代码结构优化及为屏幕阅读器生成可访问性数据。

通过在 1988 个不同移动应用的 GUI 截图上的训练与测试，UISCGD 模型在对象检测性能上达到了 77.5%的高精度，显著优于其他现有的 SOTA 模型。此外，通过一系列的实证研究，证实了该模型在感知组生成、UI 代码自动生成和生成屏幕阅读器的可访问性数据等方面的应用效果。UISCGD 模型的成功应用展示了深度学习技术在 UI 元素分组领域的巨大潜力。该研究不仅提高了 UI 元素分组的准确性和通用性，还为未来在不同平台和设备上的 UI 设计和开发提供了有力的技术支持。未来的工作将探索如何进一步提高模型的泛化能力，并扩展到更多的 UI 设计和开发场景中。

{{< figure src="ui_seg.png">}}
