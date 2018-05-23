---
layout: post
title: "Deep Learning Inference on Embedded Devices: Fixed-Point vs Posit"
date: 2018-05-22 14:31:27
categories: arXiv_CV
tags: arXiv_CV CNN Optimization Inference Deep_Learning
author: Seyed H. F. Langroudi, Tej Pandit, Dhireesha Kudithipudi
mathjax: true
---

* content
{:toc}

##### Abstract
Performing the inference step of deep learning in resource constrained environments, such as embedded devices, is challenging. Success requires optimization at both software and hardware levels. Low precision arithmetic and specifically low precision fixed-point number systems have become the standard for performing deep learning inference. However, representing non-uniform data and distributed parameters (e.g. weights) by using uniformly distributed fixed-point values is still a major drawback when using this number system. Recently, the posit number system was proposed, which represents numbers in a non-uniform manner. Therefore, in this paper we are motivated to explore using the posit number system to represent the weights of Deep Convolutional Neural Networks. However, we do not apply any quantization techniques and hence the network weights do not require re-training. The results of this exploration show that using the posit number system outperformed the fixed point number system in terms of accuracy and memory utilization.

##### Abstract (translated by Google)
在嵌入式设备等资源受限环境中执行深度学习的推理步骤具有挑战性。成功需要在软件和硬件两个层面进行优化。低精度算术和特别低精度的定点数系统已经成为进行深度学习推理的标准。然而，当使用这个数字系统时，通过使用均匀分布的定点值来表示非统一数据和分布参数（例如权重）仍然是主要缺点。最近，提出了位置数字系统，它以不均匀的方式表示数字。因此，在本文中，我们有兴趣探索使用位数系统来表示深度卷积神经网络的权重。但是，我们不应用任何量化技术，因此网络权重不需要重新训练。这项研究的结果表明，在准确性和存储器利用率方面，使用位数系统的性能优于定点数系统。

##### URL
[https://arxiv.org/abs/1805.08624](https://arxiv.org/abs/1805.08624)

##### PDF
[https://arxiv.org/pdf/1805.08624](https://arxiv.org/pdf/1805.08624)

