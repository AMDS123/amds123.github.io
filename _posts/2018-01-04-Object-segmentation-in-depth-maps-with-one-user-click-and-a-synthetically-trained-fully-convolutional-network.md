---
layout: post
title: "Object segmentation in depth maps with one user click and a synthetically trained fully convolutional network"
date: 2018-01-04 09:13:20
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation CNN Deep_Learning Detection
author: Matthieu Grard (imagine), Romain Br&#xe9;gier (IMAGINE), Florian Sella, Emmanuel Dellandr&#xe9;a (imagine), Liming Chen (imagine)
mathjax: true
---

* content
{:toc}

##### Abstract
With more and more household objects built on planned obsolescence and consumed by a fast-growing population, hazardous waste recycling has become a critical challenge. Given the large variability of household waste, current recycling platforms mostly rely on human operators to analyze the scene, typically composed of many object instances piled up in bulk. Helping them by robotizing the unitary extraction is a key challenge to speed up this tedious process. Whereas supervised deep learning has proven very efficient for such object-level scene understanding, e.g., generic object detection and segmentation in everyday scenes, it however requires large sets of per-pixel labeled images, that are hardly available for numerous application contexts, including industrial robotics. We thus propose a step towards a practical interactive application for generating an object-oriented robotic grasp, requiring as inputs only one depth map of the scene and one user click on the next object to extract. More precisely, we address in this paper the middle issue of object seg-mentation in top views of piles of bulk objects given a pixel location, namely seed, provided interactively by a human operator. We propose a twofold framework for generating edge-driven instance segments. First, we repurpose a state-of-the-art fully convolutional object contour detector for seed-based instance segmentation by introducing the notion of edge-mask duality with a novel patch-free and contour-oriented loss function. Second, we train one model using only synthetic scenes, instead of manually labeled training data. Our experimental results show that considering edge-mask duality for training an encoder-decoder network, as we suggest, outperforms a state-of-the-art patch-based network in the present application context.

##### Abstract (translated by Google)
随着越来越多的家庭用品逐渐过时并被迅速增长的人口消费，危险废物回收已经成为一个严峻的挑战。由于生活垃圾的变异性很大，目前的回收平台大多依靠人类操作员来分析现场，通常由大量堆积的物体组成。通过机械化一体化提取来帮助他们是加速这个乏味过程的关键挑战。然而，有监督的深度学习已经被证明对于这样的对象级场景理解（例如，日常场景中的通用对象检测和分割）是非常有效的，然而，其需要大量的每像素标记图像集，几乎不可用于许多应用环境，包括工业机器人。因此，我们提出了一个实用的交互式应用程序，用于生成面向对象的机器人抓握，只需输入一个场景的深度图，一个用户点击下一个要提取的对象。更确切地说，我们在本文中讨论了在像素位置的大堆物体的顶视图中的物体分割的中间问题，即种子，由操作员交互提供。我们提出了生成边缘驱动实例段的双重框架。首先，我们通过引入边缘 - 掩蔽对偶的概念和新的无补丁和轮廓定向损失函数，为基于种子的实例分割重新设计了最先进的完全卷积对象轮廓检测器。其次，我们仅使用人造场景来训练一个模型，而不是手动标记的训练数据。我们的实验结果表明，考虑到我们提出的编码器 - 解码器网络的边缘 - 掩码对偶性，在当前的应用环境中胜过了最先进的基于补丁的网络。

##### URL
[http://arxiv.org/abs/1801.01281](http://arxiv.org/abs/1801.01281)

##### PDF
[http://arxiv.org/pdf/1801.01281](http://arxiv.org/pdf/1801.01281)

