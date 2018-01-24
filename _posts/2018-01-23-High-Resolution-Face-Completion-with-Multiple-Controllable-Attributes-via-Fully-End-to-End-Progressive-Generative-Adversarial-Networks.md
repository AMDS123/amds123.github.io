---
layout: post
title: "High Resolution Face Completion with Multiple Controllable Attributes via Fully End-to-End Progressive Generative Adversarial Networks"
date: 2018-01-23 16:12:26
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Face Inference Deep_Learning
author: Zeyuan Chen, Shaoliang Nie, Tianfu Wu, Christopher G. Healey
mathjax: true
---

* content
{:toc}

##### Abstract
We present a deep learning approach for high resolution face completion with multiple controllable attributes (e.g., male and smiling) under arbitrary masks. Face completion entails understanding both structural meaningfulness and appearance consistency locally and globally to fill in "holes" whose content do not appear elsewhere in an input image. It is a challenging task with the difficulty level increasing significantly with respect to high resolution, the complexity of "holes" and the controllable attributes of filled-in fragments. Our system addresses the challenges by learning a fully end-to-end framework that trains generative adversarial networks (GANs) progressively from low resolution to high resolution with conditional vectors encoding controllable attributes. 
 We design novel network architectures to exploit information across multiple scales effectively and efficiently. We introduce new loss functions encouraging sharp completion. We show that our system can complete faces with large structural and appearance variations using a single feed-forward pass of computation with mean inference time of 0.007 seconds for images at 1024 x 1024 resolution. We also perform a pilot human study that shows our approach outperforms state-of-the-art face completion methods in terms of rank analysis. The code will be released upon publication.

##### Abstract (translated by Google)
我们提出了一个深度的学习方法，高分辨率面部完成与多个可控属性（例如，男性和微笑）在任意掩码下。面孔完成需要理解本地和全局的结构意义和外观一致性，以填充其内容不会出现在输入图像的其他地方的“孔”。这是一个具有挑战性的任务，难度水平在高分辨率，“孔”的复杂性和填充片段的可控属性方面显着增加。我们的系统通过学习完全端到端的框架来解决这些挑战，该框架通过编码可控属性的条件向量逐步地将生成对抗网络（GAN）从低分辨率向高分辨率进行训练。
 我们设计新颖的网络架构，可以有效和高效地利用多种规模的信息。我们引入新的损失函数鼓励大幅完成。我们表明，我们的系统可以用1024×1024分辨率的图像的平均推理时间为0.007秒的计算的单前馈通道来完成具有较大结构和外观变化的面部。我们还进行了一项试点人类研究，表明我们的方法在等级分析方面胜过了最先进的面孔完成方法。代码将在发布后发布。

##### URL
[http://arxiv.org/abs/1801.07632](http://arxiv.org/abs/1801.07632)

##### PDF
[http://arxiv.org/pdf/1801.07632](http://arxiv.org/pdf/1801.07632)

