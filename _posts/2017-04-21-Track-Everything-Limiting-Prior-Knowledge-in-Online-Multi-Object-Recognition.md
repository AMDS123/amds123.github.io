---
layout: post
title: "Track Everything: Limiting Prior Knowledge in Online Multi-Object Recognition"
date: 2017-04-21 06:49:51
categories: arXiv_CV
tags: arXiv_CV Knowledge Tracking CNN Classification Detection Recognition
author: Sebastien C. Wong, Victor Stamatescu, Adam Gatt, David Kearney, Ivan Lee, Mark D. McDonnell
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the problem of online tracking and classification of multiple objects in an image sequence. Our proposed solution is to first track all objects in the scene without relying on object-specific prior knowledge, which in other systems can take the form of hand-crafted features or user-based track initialization. We then classify the tracked objects with a fast-learning image classifier that is based on a shallow convolutional neural network architecture and demonstrate that object recognition improves when this is combined with object state information from the tracking algorithm. We argue that by transferring the use of prior knowledge from the detection and tracking stages to the classification stage we can design a robust, general purpose object recognition system with the ability to detect and track a variety of object types. We describe our biologically inspired implementation, which adaptively learns the shape and motion of tracked objects, and apply it to the Neovision2 Tower benchmark data set, which contains multiple object types. An experimental evaluation demonstrates that our approach is competitive with state-of-the-art video object recognition systems that do make use of object-specific prior knowledge in detection and tracking, while providing additional practical advantages by virtue of its generality.

##### Abstract (translated by Google)
本文针对图像序列中多个对象的在线跟踪和分类问题。我们提出的解决方案是首先跟踪场景中的所有对象，而不依赖于特定于对象的先验知识，在其他系统中可以采取手工特征或基于用户的轨迹初始化的形式。然后，我们使用基于浅卷积神经网络架构的快速学习图像分类器对跟踪的对象进行分类，并且证明当跟踪算法中的对象状态信息与对象识别相结合时，对象识别效果得到改善。我们认为，通过将先验知识从检测和跟踪阶段转移到分类阶段，我们可以设计一个强大的通用目标识别系统，能够检测和跟踪多种目标类型。我们描述了我们的生物启发式实现，它自适应地学习跟踪对象的形状和运动，并将其应用于包含多个对象类型的Neovision2 Tower基准数据集。实验评估表明，我们的方法与最先进的视频对象识别系统相比具有竞争力，该系统在检测和跟踪中利用了特定于对象的先验知识，同时凭借其通用性提供了额外的实用优势。

##### URL
[https://arxiv.org/abs/1704.06415](https://arxiv.org/abs/1704.06415)

##### PDF
[https://arxiv.org/pdf/1704.06415](https://arxiv.org/pdf/1704.06415)

