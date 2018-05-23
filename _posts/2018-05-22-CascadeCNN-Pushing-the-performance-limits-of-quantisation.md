---
layout: post
title: "CascadeCNN: Pushing the performance limits of quantisation"
date: 2018-05-22 17:06:02
categories: arXiv_AI
tags: arXiv_AI Inference
author: Alexandros Kouris, Stylianos I. Venieris, Christos-Savvas Bouganis
mathjax: true
---

* content
{:toc}

##### Abstract
This work presents CascadeCNN, an automated toolflow that pushes the quantisation limits of any given CNN model, to perform high-throughput inference by exploiting the computation time-accuracy trade-off. Without the need for retraining, a two-stage architecture tailored for any given FPGA device is generated, consisting of a low- and a high-precision unit. A confidence evaluation unit is employed between them to identify misclassified cases at run time and forward them to the high-precision unit or terminate computation. Experiments demonstrate that CascadeCNN achieves a performance boost of up to 55% for VGG-16 and 48% for AlexNet over the baseline design for the same resource budget and accuracy.

##### Abstract (translated by Google)
这项工作提供CascadeCNN，一个自动化工具流程，推动任何给定的CNN模型的量化限制，通过利用计算时间 - 精度折衷来执行高吞吐量推断。无需再培训，可为任何给定的FPGA器件量身定制两级架构，包括低精度和高精度单元。它们之间采用置信度评估单元，以在运行时识别错误分类的案例，并将其转发给高精度单元或终止计算。实验表明，CascadeCNN对于相同的资源预算和准确度，VGG-16和AlexNet的基线设计性能提升高达55％，AlexNet提升48％。

##### URL
[https://arxiv.org/abs/1805.08743](https://arxiv.org/abs/1805.08743)

##### PDF
[https://arxiv.org/pdf/1805.08743](https://arxiv.org/pdf/1805.08743)

