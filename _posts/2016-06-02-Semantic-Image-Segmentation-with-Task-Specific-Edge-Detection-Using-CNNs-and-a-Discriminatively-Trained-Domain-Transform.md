---
layout: post
title: "Semantic Image Segmentation with Task-Specific Edge Detection Using CNNs and a Discriminatively Trained Domain Transform"
date: 2016-06-02 02:11:07
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Inference Detection
author: Liang-Chieh Chen, Jonathan T. Barron, George Papandreou, Kevin Murphy, Alan L. Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolutional neural networks (CNNs) are the backbone of state-of-art semantic image segmentation systems. Recent work has shown that complementing CNNs with fully-connected conditional random fields (CRFs) can significantly enhance their object localization accuracy, yet dense CRF inference is computationally expensive. We propose replacing the fully-connected CRF with domain transform (DT), a modern edge-preserving filtering method in which the amount of smoothing is controlled by a reference edge map. Domain transform filtering is several times faster than dense CRF inference and we show that it yields comparable semantic segmentation results, accurately capturing object boundaries. Importantly, our formulation allows learning the reference edge map from intermediate CNN features instead of using the image gradient magnitude as in standard DT filtering. This produces task-specific edges in an end-to-end trainable system optimizing the target semantic segmentation quality.

##### Abstract (translated by Google)
深卷积神经网络（CNN）是最先进的语义图像分割系统的骨干。最近的研究表明，使用完全连接的条件随机场（CRF）来补充CNN可以显着提高其对象定位精度，但是密集的CRF推断在计算上是昂贵的。我们建议用域变换（DT）代替全连接的CRF，所述域变换是一种现代的边缘保持滤波方法，其中平滑量由参考边缘图来控制。域变换过滤比密集CRF推理快几倍，我们证明它产生可比较的语义分割结果，准确地捕获对象边界。重要的是，我们的公式允许从中间CNN特征学习参考边缘图，而不是象在标准DT滤波中那样使用图像梯度幅度。这在端到端可训练系统中产生特定于任务的边缘，从而优化目标语义分割质量。

##### URL
[https://arxiv.org/abs/1511.03328](https://arxiv.org/abs/1511.03328)

##### PDF
[https://arxiv.org/pdf/1511.03328](https://arxiv.org/pdf/1511.03328)

