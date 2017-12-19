---
layout: post
title: "R-CNN minus R"
date: 2015-06-23 13:26:36
categories: arXiv_CV
tags: arXiv_CV Image_Caption Object_Detection CNN Detection
author: Karel Lenc, Andrea Vedaldi
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolutional neural networks (CNNs) have had a major impact in most areas of image understanding, including object category detection. In object detection, methods such as R-CNN have obtained excellent results by integrating CNNs with region proposal generation algorithms such as selective search. In this paper, we investigate the role of proposal generation in CNN-based detectors in order to determine whether it is a necessary modelling component, carrying essential geometric information not contained in the CNN, or whether it is merely a way of accelerating detection. We do so by designing and evaluating a detector that uses a trivial region generation scheme, constant for each image. Combined with SPP, this results in an excellent and fast detector that does not require to process an image with algorithms other than the CNN itself. We also streamline and simplify the training of CNN-based detectors by integrating several learning steps in a single algorithm, as well as by proposing a number of improvements that accelerate detection.

##### Abstract (translated by Google)
深度卷积神经网络（CNNs）已经在图像理解的大部分领域产生了重大影响，包括对象类别检测。在对象检测中，R-CNN等方法通过集成CNN和区域提议生成算法（如选择性搜索）获得了优异的结果。在本文中，我们调查提案生成在基于CNN的探测器中的角色，以确定它是否是必要的建模组件，携带CNN中未包含的基本几何信息，还是仅仅是加速探测的一种方式。我们通过设计和评估使用平凡区域生成方案的检测器来实现这一点，对于每个图像常量。与SPP相结合，这导致了一个优秀和快速的检测器，不需要使用CNN本身以外的算法处理图像。我们还简化了基于CNN的检测器的培训，将几个学习步骤集成在一个算法中，并提出了一些加速检测的改进。

##### URL
[https://arxiv.org/abs/1506.06981](https://arxiv.org/abs/1506.06981)

##### PDF
[https://arxiv.org/pdf/1506.06981](https://arxiv.org/pdf/1506.06981)

