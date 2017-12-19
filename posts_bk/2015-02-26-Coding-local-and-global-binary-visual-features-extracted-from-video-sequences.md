---
layout: post
title: "Coding local and global binary visual features extracted from video sequences"
date: 2015-02-26 14:23:39
categories: arXiv_CV
tags: arXiv_CV
author: Luca Baroffio, Antonio Canclini, Matteo Cesana, Alessandro Redondi, Marco Tagliasacchi, Stefano Tubaro
mathjax: true
---

* content
{:toc}

##### Abstract
Binary local features represent an effective alternative to real-valued descriptors, leading to comparable results for many visual analysis tasks, while being characterized by significantly lower computational complexity and memory requirements. When dealing with large collections, a more compact representation based on global features is often preferred, which can be obtained from local features by means of, e.g., the Bag-of-Visual-Word (BoVW) model. Several applications, including for example visual sensor networks and mobile augmented reality, require visual features to be transmitted over a bandwidth-limited network, thus calling for coding techniques that aim at reducing the required bit budget, while attaining a target level of efficiency. In this paper we investigate a coding scheme tailored to both local and global binary features, which aims at exploiting both spatial and temporal redundancy by means of intra- and inter-frame coding. In this respect, the proposed coding scheme can be conveniently adopted to support the Analyze-Then-Compress (ATC) paradigm. That is, visual features are extracted from the acquired content, encoded at remote nodes, and finally transmitted to a central controller that performs visual analysis. This is in contrast with the traditional approach, in which visual content is acquired at a node, compressed and then sent to a central unit for further processing, according to the Compress-Then-Analyze (CTA) paradigm. In this paper we experimentally compare ATC and CTA by means of rate-efficiency curves in the context of two different visual analysis tasks: homography estimation and content-based retrieval. Our results show that the novel ATC paradigm based on the proposed coding primitives can be competitive with CTA, especially in bandwidth limited scenarios.

##### Abstract (translated by Google)
二进制局部特征代表了实值描述符的有效替代方法，为许多视觉分析任务带来可比较的结果，同时具有显着较低的计算复杂度和内存要求。当处理大的集合时，基于全局特征的更紧凑的表示通常是优选的，其可以通过例如视觉文字袋（BoVW）模型从局部特征获得。包括例如视觉传感器网络和移动增强现实在内的多种应用需要通过带宽有限的网络传输视觉特征，因此需要旨在减少所需比特预算的编码技术，同时达到目标效率水平。在本文中，我们调查了针对局部和全局二进制特征量身定制的编码方案，其目的在于通过帧内和帧间编码来利用空间和时间冗余。在这方面，可以方便地采用所提出的编码方案来支持分析 - 压缩（ATC）范例。也就是说，从获取的内容中提取视觉特征，在远程节点编码，最后传输到执行视觉分析的中央控制器。这与传统的方法相反，根据压缩 - 然后分析（CTA）范例，在节点上获取视觉内容，压缩然后发送到中央单元进行进一步处理。在本文中，我们通过在两种不同的视觉分析任务中的速率 - 效率曲线来比较ATC和CTA：单应性估计和基于内容的检索。我们的研究结果表明，基于提出的编码原语的新颖的ATC范式可以与CTA竞争，特别是在带宽有限的情况下。

##### URL
[https://arxiv.org/abs/1502.07939](https://arxiv.org/abs/1502.07939)

##### PDF
[https://arxiv.org/pdf/1502.07939](https://arxiv.org/pdf/1502.07939)

