---
layout: post
title: "PerforatedCNNs: Acceleration through Elimination of Redundant Convolutions"
date: 2016-10-16 02:00:47
categories: arXiv_CV
tags: arXiv_CV CNN Optimization
author: Michael Figurnov, Aijan Ibraimova, Dmitry Vetrov, Pushmeet Kohli
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel approach to reduce the computational cost of evaluation of convolutional neural networks, a factor that has hindered their deployment in low-power devices such as mobile phones. Inspired by the loop perforation technique from source code optimization, we speed up the bottleneck convolutional layers by skipping their evaluation in some of the spatial positions. We propose and analyze several strategies of choosing these positions. We demonstrate that perforation can accelerate modern convolutional networks such as AlexNet and VGG-16 by a factor of 2x - 4x. Additionally, we show that perforation is complementary to the recently proposed acceleration method of Zhang et al.

##### Abstract (translated by Google)
我们提出了一种新的方法来降低卷积神经网络评估的计算成本，这是妨碍其在诸如移动电话的低功率设备中部署的一个因素。受源代码优化中的循环穿孔技术的启发，我们通过跳过其在某些空间位置上的评估来加速卷积层的瓶颈。我们提出并分析选择这些职位的几种策略。我们证明，穿孔可以加速现代卷积网络，比如AlexNet和VGG-16，达到2x  -  4倍。另外，我们表明，穿孔是补充张最近提出的加速方法等。

##### URL
[https://arxiv.org/abs/1504.08362](https://arxiv.org/abs/1504.08362)

##### PDF
[https://arxiv.org/pdf/1504.08362](https://arxiv.org/pdf/1504.08362)

