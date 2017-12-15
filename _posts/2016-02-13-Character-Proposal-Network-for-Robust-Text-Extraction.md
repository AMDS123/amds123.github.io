---
layout: post
title: "Character Proposal Network for Robust Text Extraction"
date: 2016-02-13 15:55:17
categories: arXiv_CV
tags: arXiv_CV CNN Detection
author: Shuye Zhang, Mude Lin, Tianshui Chen, Lianwen Jin, Liang Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Maximally stable extremal regions (MSER), which is a popular method to generate character proposals/candidates, has shown superior performance in scene text detection. However, the pixel-level operation limits its capability for handling some challenging cases (e.g., multiple connected characters, separated parts of one character and non-uniform illumination). To better tackle these cases, we design a character proposal network (CPN) by taking advantage of the high capacity and fast computing of fully convolutional network (FCN). Specifically, the network simultaneously predicts characterness scores and refines the corresponding locations. The characterness scores can be used for proposal ranking to reject non-character proposals and the refining process aims to obtain the more accurate locations. Furthermore, considering the situation that different characters have different aspect ratios, we propose a multi-template strategy, designing a refiner for each aspect ratio. The extensive experiments indicate our method achieves recall rates of 93.88%, 93.60% and 96.46% on ICDAR 2013, SVT and Chinese2k datasets respectively using less than 1000 proposals, demonstrating promising performance of our character proposal network.

##### Abstract (translated by Google)
最稳定的极值区域（MSER）是生成角色提议/候选的流行方法，在场景文本检测中表现出优越的性能。然而，像素级操作限制了其处理一些具有挑战性的情况（例如，多个连接字符，一个字符的分离部分和不均匀照明）的能力。为了更好地处理这些情况，我们利用全卷积网络（FCN）的高容量和快速计算来设计角色提议网络（CPN）。具体来说，网络可以同时预测角色分数并细化相应的位置。角色分数可用于提案排名，拒绝非角色提案，提炼过程旨在获得更准确的位置。此外，针对不同角色具有不同宽高比的情况，提出了一种多模板策略，针对每一个长宽比设计了一个磨浆机。广泛的实验表明，我们的方法在ICDAR 2013，SVT和Chinese2k数据集中的召回率分别达到93.88％，93.60％和96.46％，分别使用少于1000个提案，这表明我们的角色提案网络表现出色。

##### URL
[https://arxiv.org/abs/1602.04348](https://arxiv.org/abs/1602.04348)

##### PDF
[https://arxiv.org/pdf/1602.04348](https://arxiv.org/pdf/1602.04348)

