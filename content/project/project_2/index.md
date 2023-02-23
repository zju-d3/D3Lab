---
title: 电商平台中不同购物场景下的布局生成
authors:
  - 陈柳青
  - jqz
  - zyx


date: 2022-10-18
weight: 10

math: true
highlight: true

tags:
  - UI
  
# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false


---
布局生成，深度生成模型，用户界面设计，商品展示页面
<!--more-->

## 项目简介

布局是移动购物应用程序的商品展示页面中至关重要的一部分。为了清楚、准确地传达消费者所需的商品信息，商品展示页面（Product Listing Pages, PLP）的布局设计通常由其购物场景驱动。在这项工作中，我们研究了针对不同场景的布局设计，并提出了一个设计空间来指导PLP的布局生成和评估。此外，我们还提出了一个布局生成模型，LayoutVQ-VAE，该模型以用户输入的布局应用场景和元素类别为约束，能够生成满足约束的高质量布局。LayoutVQ-VAE也可以应用于文档布局、杂志布局、手机UI布局等相关的设计任务中。

{{< video src="Layout Generation for Various Scenarios in Mobile Shopping Apps.mp4" controls="yes" >}}
