---
layout: post
title: "A Novel Scene Text Detection Algorithm Based On Convolutional Neural Network"
date: 2016-04-07 07:16:35
categories: arXiv_CV
tags: arXiv_CV CNN Detection Relation
author: Xiaohang Ren, Kai Chen, Jun Sun
mathjax: true
---

* content
{:toc}

##### Abstract
Candidate text region extraction plays a critical role in convolutional neural network (CNN) based text detection from natural images. In this paper, we propose a CNN based scene text detection algorithm with a new text region extractor. The so called candidate text region extractor I-MSER is based on Maximally Stable Extremal Region (MSER), which can improve the independency and completeness of the extracted candidate text regions. Design of I-MSER is motivated by the observation that text MSERs have high similarity and are close to each other. The independency of candidate text regions obtained by I-MSER is guaranteed by selecting the most representative regions from a MSER tree which is generated according to the spatial overlapping relationship among the MSERs. A multi-layer CNN model is trained to score the confidence value of the extracted regions extracted by the I-MSER for text detection. The new text detection algorithm based on I-MSER is evaluated with wide-used ICDAR 2011 and 2013 datasets and shows improved detection performance compared to the existing algorithms.

##### Abstract (translated by Google)
候选文本区域提取在基于卷积神经网络（CNN）的自然图像文本检测中起着关键作用。在本文中，我们提出了一种新的文本区域提取器的基于CNN的场景文本检测算法。所谓候选文本区域提取器I-MSER基于最大稳定极值区域（MSER），可以提高候选文本区域的独立性和完整性。 I-MSER的设计是由文本MSER具有高度相似性和彼此接近的观察所驱动的。 I-MSER获得的候选文本区域的独立性是通过从MSER树中选择最具代表性的区域来保证的，MSER树是根据MSER之间的空间重叠关系生成的。训练多层CNN模型以对由I-MSER提取的用于文本检测的提取区域的置信度值进行评分。基于I-MSER的新的文本检测算法通过广泛使用的ICDAR 2011和2013数据集进行评估，并且与现有算法相比显示出改进的检测性能。

##### URL
[https://arxiv.org/abs/1604.01894](https://arxiv.org/abs/1604.01894)

##### PDF
[https://arxiv.org/pdf/1604.01894](https://arxiv.org/pdf/1604.01894)

