---
layout: post
title: "Radon Inversion via Deep Learning"
date: 2018-08-09 04:19:08
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Ji He, Jianhua Ma
mathjax: true
---

* content
{:toc}

##### Abstract
Radon transform is widely used in physical and life sciences and one of its major applications is the X-ray computed tomography (X-ray CT), which is significant in modern health examination. The Radon inversion or image reconstruction is challenging due to the potentially defective radon projections. Conventionally, the reconstruction process contains several ad hoc stages to approximate the corresponding Radon inversion. Each of the stages is highly dependent on the results of the previous stage. In this paper, we propose a novel unified framework for Radon inversion via deep learning (DL). The Radon inversion can be approximated by the proposed framework with an end-to-end fashion instead of processing step-by-step with multiple stages. For simplicity, the proposed framework is short as iRadonMap (inverse Radon transform approximation). Specifically, we implement the iRadonMap as an appropriative neural network, of which the architecture can be divided into two segments. In the first segment, a learnable fully-connected filtering layer is used to filter the radon projections along the view-angle direction, which is followed by a learnable sinusoidal back-projection layer to transfer the filtered radon projections into an image. The second segment is a common neural network architecture to further improve the reconstruction performance in the image domain. The iRadonMap is overall optimized by training a large number of generic images from ImageNet database. To evaluate the performance of the iRadonMap, clinical patient data is used. Qualitative results show promising reconstruction performance of the iRadonMap.

##### Abstract (translated by Google)
氡变换广泛用于物理和生命科学，其主要应用之一是X射线计算机断层扫描（X射线CT），这在现代健康检查中具有重要意义。由于可能有缺陷的氡投影，氡反转或图像重建具有挑战性。传统上，重建过程包含几个特设阶段以近似相应的Radon反演。每个阶段都高度依赖于前一阶段的结果。在本文中，我们提出了一种新的通过深度学习（DL）进行Radon反演的统一框架。 Radon反演可以通过端到端的方式与所提出的框架近似，而不是逐步处理多个阶段。为简单起见，所提出的框架简称为iRadonMap（逆Radon变换近似）。具体来说，我们将iRadonMap实现为专用神经网络，其架构可分为两个部分。在第一段中，可学习的完全连接的滤波层用于沿视角方向过滤氡投影，其后是可学习的正弦背投影层，以将滤波的氡投影转移到图像中。第二段是常见的神经网络架构，以进一步改善图像域中的重建性能。通过训练ImageNet数据库中的大量通用图像，对iRadonMap进行了全面优化。为了评估iRadonMap的性能，使用临床患者数据。定性结果显示iRadonMap具有良好的重建性能。

##### URL
[http://arxiv.org/abs/1808.03015](http://arxiv.org/abs/1808.03015)

##### PDF
[http://arxiv.org/pdf/1808.03015](http://arxiv.org/pdf/1808.03015)

