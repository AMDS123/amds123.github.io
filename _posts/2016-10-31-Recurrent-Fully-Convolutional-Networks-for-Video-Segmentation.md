---
layout: post
title: "Recurrent Fully Convolutional Networks for Video Segmentation"
date: 2016-10-31 00:05:49
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation CNN Detection
author: Sepehr Valipour, Mennatullah Siam, Martin Jagersand, Nilanjan Ray
mathjax: true
---

* content
{:toc}

##### Abstract
Image segmentation is an important step in most visual tasks. While convolutional neural networks have shown to perform well on single image segmentation, to our knowledge, no study has been been done on leveraging recurrent gated architectures for video segmentation. Accordingly, we propose a novel method for online segmentation of video sequences that incorporates temporal data. The network is built from fully convolutional element and recurrent unit that works on a sliding window over the temporal data. We also introduce a novel convolutional gated recurrent unit that preserves the spatial information and reduces the parameters learned. Our method has the advantage that it can work in an online fashion instead of operating over the whole input batch of video frames. The network is tested on the change detection dataset, and proved to have 5.5\% improvement in F-measure over a plain fully convolutional network for per frame segmentation. It was also shown to have improvement of 1.4\% for the F-measure compared to our baseline network that we call FCN 12s.

##### Abstract (translated by Google)
图像分割是大多数视觉任务中的一个重要步骤。尽管卷积神经网络在单一图像分割方面表现出色，但据我们所知，目前还没有关于利用循环门控体系结构进行视频分割的研究。因此，我们提出了一种新颖的方法，用于在线分割包含时间数据的视频序列。网络由完全卷积元素和循环单元构成，在时间数据上的滑动窗口上工作。我们还引入了一种新的卷积门控循环单元，保留了空间信息，减少了学习的参数。我们的方法的优点是，它可以在线的方式工作，而不是在整个输入批次的视频帧上进行操作。该网络在变化检测数据集上进行测试，并证明在每帧分割的普通完全卷积网络上F-测量值有5.5％的改进。与我们称为FCN 12s的基线网络相比，F-measure也显示有1.4％的改善。

##### URL
[https://arxiv.org/abs/1606.00487](https://arxiv.org/abs/1606.00487)

##### PDF
[https://arxiv.org/pdf/1606.00487](https://arxiv.org/pdf/1606.00487)

