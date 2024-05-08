---
title: Prototype2code：从UI设计原型到端到端前端代码生成
authors:
  - 陈柳青
  - xsh
  - ljz
  - cyn

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

UI Automation, Front-end Code Generation, Design Linting, Software Engineering

<!--more-->

## 项目简介

传统的 UI 到代码的转换技术通常依赖于设计原型的质量，而这些原型的质量参差不齐，常导致生成的代码结构混乱、不支持响应式布局等问题。本研究提出的 Prototype2Code 通过整合设计原型的语法检查，针对发现的元素碎片和感知分组进行优化，提高了代码的可读性和结构清晰度。在技术实现上，Prototype2Code 应用图神经网络和大型语言模型，自动从 UI 原型中识别和分类 UI 元素，如文本、图片和列表项，并基于这些信息构建 HTML 骨架代码和 CSS 样式代码。系统支持弹性盒子（flexbox）布局模型，确保生成的代码可以适配不同设备大小。

研究通过与商业代码生成平台 CodeFun 和基于 GPT-4v 的 Screenshot-to-code 系统的比较，展示了 Prototype2Code 在视觉相似度和代码质量上的优势。使用 SSIM、PSNR 和 MSE 等指标评估显示，Prototype2Code 生成的 UI 效果与设计原型的一致性最高，错误最少。此外，通过用户研究，Prototype2Code 在代码的可读性、可用性和可维护性方面均优于对比系统。Prototype2Code 系统成功地展示了在前端代码生成中整合原型整理和智能识别技术的潜力。未来工作将探索支持动态页面生成、增强与前端开发框架的兼容性，以及开发可交互的视觉平台以进一步提高工程师的操作自由度。
