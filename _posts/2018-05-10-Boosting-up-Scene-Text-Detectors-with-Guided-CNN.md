---
layout: post
title: "Boosting up Scene Text Detectors with Guided CNN"
date: 2018-05-10 18:51:19
categories: arXiv_CV
tags: arXiv_CV Object_Detection Attention Detection
author: Xiaoyu Yu, Zhanghui Kuang, Zhaoyang Zhang, Zhenfang Chen, Pan He, Yu Qiao, Wei Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Deep CNNs have achieved great success in text detection. Most of existing methods attempt to improve accuracy with sophisticated network design, while paying less attention on speed. In this paper, we propose a general framework for text detection called Guided CNN to achieve the two goals simultaneously. The proposed model consists of one guidance subnetwork, where a guidance mask is learned from the input image itself, and one primary text detector, where every convolution and non-linear operation are conducted only in the guidance mask. On the one hand, the guidance subnetwork filters out non-text regions coarsely, greatly reduces the computation complexity. On the other hand, the primary text detector focuses on distinguishing between text and hard non-text regions and regressing text bounding boxes, achieves a better detection accuracy. A training strategy, called background-aware block-wise random synthesis, is proposed to further boost up the performance. We demonstrate that the proposed Guided CNN is not only effective but also efficient with two state-of-the-art methods, CTPN and EAST, as backbones. On the challenging benchmark ICDAR 2013, it speeds up CTPN by 2.9 times on average, while improving the F-measure by 1.5%. On ICDAR 2015, it speeds up EAST by 2.0 times while improving the F-measure by 1.0%.

##### Abstract (translated by Google)
深度CNN在文本检测方面取得了巨大成功。现有的大多数方法都试图通过复杂的网络设计来提高准确性，同时对速度关注较少。在本文中，我们提出了一个称为引导CNN的文本检测的通用框架，以同时实现这两个目标。所提出的模型由一个引导子网络和一个主要文本探测器组成，其中从输入图像本身学习引导掩模，其中每个卷积和非线性操作仅在引导掩模中进行。一方面，引导子网粗略过滤掉非文本区域，大大降低了计算复杂度。另一方面，主文本检测器侧重于区分文本和硬非文本区域并回归文本边界框，实现更好的检测精度。为了进一步提高性能，提出了一种称为背景感知块分块随机综合的训练策略。我们证明，提出的引导性CNN不仅有效，而且以两种最先进的方法CTPN和EAST作为骨干也是有效的。在具有挑战性的基准ICDAR 2013上，它平均加速CTPN 2.9倍，同时将F-measure提高1.5％。在ICDAR 2015上，它将EAST速度提高了2.0倍，同时将F-measure提高了1.0％。

##### URL
[http://arxiv.org/abs/1805.04132](http://arxiv.org/abs/1805.04132)

##### PDF
[http://arxiv.org/pdf/1805.04132](http://arxiv.org/pdf/1805.04132)

