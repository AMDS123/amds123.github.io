---
layout: post
title: "PVANET: Deep but Lightweight Neural Networks for Real-time Object Detection"
date: 2016-09-30 07:17:13
categories: arXiv_CV
tags: arXiv_CV Object_Detection Classification Detection
author: Kye-Hyeon Kim, Sanghoon Hong, Byungseok Roh, Yeongjae Cheon, Minje Park
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents how we can achieve the state-of-the-art accuracy in multi-category object detection task while minimizing the computational cost by adapting and combining recent technical innovations. Following the common pipeline of "CNN feature extraction + region proposal + RoI classification", we mainly redesign the feature extraction part, since region proposal part is not computationally expensive and classification part can be efficiently compressed with common techniques like truncated SVD. Our design principle is "less channels with more layers" and adoption of some building blocks including concatenated ReLU, Inception, and HyperNet. The designed network is deep and thin and trained with the help of batch normalization, residual connections, and learning rate scheduling based on plateau detection. We obtained solid results on well-known object detection benchmarks: 83.8% mAP (mean average precision) on VOC2007 and 82.5% mAP on VOC2012 (2nd place), while taking only 750ms/image on Intel i7-6700K CPU with a single core and 46ms/image on NVIDIA Titan X GPU. Theoretically, our network requires only 12.3% of the computational cost compared to ResNet-101, the winner on VOC2012.

##### Abstract (translated by Google)
本文介绍了如何通过适应和结合最近的技术创新来实现多类别对象检测任务中的最新精度，同时最小化计算成本。继“CNN特征提取+地区提案+ RoI分类”这一常用的流水线之后，我们主要重新设计特征提取部分，因为地区提案部分计算起来并不昂贵，分类部分可以用截短奇异值分解（SVD）等常用技术进行有效压缩。我们的设计原则是“更少层次的渠道”，并采用了ReLU，Inception和HyperNet等一些构建模块。利用批量归一化，残留连接，基于平台检测的学习速率调度，设计的网络深入细致。我们在众所周知的目标检测基准上获得了可靠的结果：在VOC2007上的平均精确度为83.8％，在VOC2012上的平均精度为82.5％（第二位），而单核心的Intel i7-6700K CPU上的图像仅为750ms / NVIDIA Titan X GPU上46ms /图像。从理论上说，我们的网络只需要12.3％的计算成本，而ResNet-101则是VOC2012的赢家。

##### URL
[https://arxiv.org/abs/1608.08021](https://arxiv.org/abs/1608.08021)

##### PDF
[https://arxiv.org/pdf/1608.08021](https://arxiv.org/pdf/1608.08021)

