---
layout: post
title: "SFCN-OPI: Detection and Fine-grained Classification of Nuclei Using Sibling FCN with Objectness Prior Interaction"
date: 2017-12-22 03:56:56
categories: arXiv_CV
tags: arXiv_CV CNN Classification Detection
author: Yanning Zhou, Qi Dou, Hao Chen, Jing Qin, Pheng-Ann Heng
mathjax: true
---

* content
{:toc}

##### Abstract
Cell nuclei detection and fine-grained classification have been fundamental yet challenging problems in histopathology image analysis. Due to the nuclei tiny size, significant inter-/intra-class variances, as well as the inferior image quality, previous automated methods would easily suffer from limited accuracy and robustness. In the meanwhile, existing approaches usually deal with these two tasks independently, which would neglect the close relatedness of them. In this paper, we present a novel method of sibling fully convolutional network with prior objectness interaction (called SFCN-OPI) to tackle the two tasks simultaneously and interactively using a unified end-to-end framework. Specifically, the sibling FCN branches share features in earlier layers while holding respective higher layers for specific tasks. More importantly, the detection branch outputs the objectness prior which dynamically interacts with the fine-grained classification sibling branch during the training and testing processes. With this mechanism, the fine-grained classification successfully focuses on regions with high confidence of nuclei existence and outputs the conditional probability, which in turn benefits the detection through back propagation. Extensive experiments on colon cancer histology images have validated the effectiveness of our proposed SFCN-OPI and our method has outperformed the state-of-the-art methods by a large margin.

##### Abstract (translated by Google)
细胞核检测和细粒度分类是组织病理学图像分析中的基本问题，也是挑战性的问题。由于原子核的尺寸很小，显着的类内/类内差异以及较差的图像质量，以前的自动化方法很容易遭受有限的精度和鲁棒性。同时，现有方法通常独立处理这两个任务，忽视了它们之间的紧密联系。在本文中，我们提出了一种全新的具有先验对象交互的卷积网络（称为SFCN-OPI）的方法，使用统一的端到端框架来同时交互地处理这两个任务。具体而言，兄弟FCN分支在先前的层中共享特征，同时为特定的任务保持相应的更高层。更重要的是，检测分支在训练和测试过程中输出之前与细粒度分类兄弟分支动态交互的对象。通过这种机制，细粒度的分类成功地集中在核心存在的高可信度区域，并输出条件概率，这反过来有利于通过反向传播进行检测。对结肠癌组织学图像的大量实验验证了我们提出的SFCN-OPI的有效性，并且我们的方法大大超过了最先进的方法。

##### URL
[https://arxiv.org/abs/1712.08297](https://arxiv.org/abs/1712.08297)

##### PDF
[https://arxiv.org/pdf/1712.08297](https://arxiv.org/pdf/1712.08297)

