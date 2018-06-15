---
layout: post
title: "Dynamic Video Segmentation Network"
date: 2018-06-14 12:11:48
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation
author: Yu-Syuan Xu, Tsu-Jui Fu, Hsuan-Kung Yang, Chun-Yi Lee
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a detailed design of dynamic video segmentation network (DVSNet) for fast and efficient semantic video segmentation. DVSNet consists of two convolutional neural networks: a segmentation network and a flow network. The former generates highly accurate semantic segmentations, but is deeper and slower. The latter is much faster than the former, but its output requires further processing to generate less accurate semantic segmentations. We explore the use of a decision network to adaptively assign different frame regions to different networks based on a metric called expected confidence score. Frame regions with a higher expected confidence score traverse the flow network. Frame regions with a lower expected confidence score have to pass through the segmentation network. We have extensively performed experiments on various configurations of DVSNet, and investigated a number of variants for the proposed decision network. The experimental results show that our DVSNet is able to achieve up to 70.4% mIoU at 19.8 fps on the Cityscape dataset. A high speed version of DVSNet is able to deliver an fps of 30.4 with 63.2% mIoU on the same dataset. DVSNet is also able to reduce up to 95% of the computational workloads.

##### Abstract (translated by Google)
在本文中，我们提出了一个动态视频分割网络（DVSNet）的详细设计，用于快速高效的语义视频分割。 DVSNet由两个卷积神经网络组成：分割网络和流动网络。前者产生高度准确的语义分割，但更深入和更慢。后者比前者快得多，但其输出需要进一步处理以产生较不准确的语义分段。我们探索使用决策网络来根据称为预期置信度分数的度量自适应地将不同的帧区域分配给不同的网络。具有较高预期置信度得分的帧区域遍历流网络。具有较低预期置信度得分的帧区域必须通过分割网络。我们已经广泛地对DVSNet的各种配置进行了实验，并针对所提出的决策网络研究了许多变体。实验结果表明，我们的DVSNet能够在Cityscape数据集上以19.8 fps达到70.4％mIoU。 DVSNet的高速版本能够在相同的数据集上提供30.4的fps和63.2％的mIoU。 DVSNet还可以减少高达95％的计算工作量。

##### URL
[http://arxiv.org/abs/1804.00931](http://arxiv.org/abs/1804.00931)

##### PDF
[http://arxiv.org/pdf/1804.00931](http://arxiv.org/pdf/1804.00931)

