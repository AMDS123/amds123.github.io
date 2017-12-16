---
layout: post
title: "Fine-grained Recurrent Neural Networks for Automatic Prostate Segmentation in Ultrasound Images"
date: 2016-12-06 03:56:07
categories: arXiv_CV
tags: arXiv_CV Segmentation RNN Prediction
author: Xin Yang, Lequan Yu, Lingyun Wu, Yi Wang, Dong Ni, Jing Qin, Pheng-Ann Heng
mathjax: true
---

* content
{:toc}

##### Abstract
Boundary incompleteness raises great challenges to automatic prostate segmentation in ultrasound images. Shape prior can provide strong guidance in estimating the missing boundary, but traditional shape models often suffer from hand-crafted descriptors and local information loss in the fitting procedure. In this paper, we attempt to address those issues with a novel framework. The proposed framework can seamlessly integrate feature extraction and shape prior exploring, and estimate the complete boundary with a sequential manner. Our framework is composed of three key modules. Firstly, we serialize the static 2D prostate ultrasound images into dynamic sequences and then predict prostate shapes by sequentially exploring shape priors. Intuitively, we propose to learn the shape prior with the biologically plausible Recurrent Neural Networks (RNNs). This module is corroborated to be effective in dealing with the boundary incompleteness. Secondly, to alleviate the bias caused by different serialization manners, we propose a multi-view fusion strategy to merge shape predictions obtained from different perspectives. Thirdly, we further implant the RNN core into a multiscale Auto-Context scheme to successively refine the details of the shape prediction map. With extensive validation on challenging prostate ultrasound images, our framework bridges severe boundary incompleteness and achieves the best performance in prostate boundary delineation when compared with several advanced methods. Additionally, our approach is general and can be extended to other medical image segmentation tasks, where boundary incompleteness is one of the main challenges.

##### Abstract (translated by Google)
边界不完全性对超声图像中的自动前列腺分割提出了巨大的挑战。形状优先可以为估计缺失边界提供有力的指导，但是传统的形状模型在拟合过程中经常遭受手工描述和局部信息损失。在本文中，我们试图用一个新的框架来解决这些问题。所提出的框架可以将特征提取和形状先前的探索无缝集成，并以顺序的方式估计完整的边界。我们的框架由三个关键模块组成。首先，将静态2D前列腺超声图像序列化为动态序列，然后通过依次探索形状先验来预测前列腺形状。直觉上，我们建议在生物学上合理的递归神经网络（RNN）之前学习形状。这个模块被证实对于处理边界不完整性是有效的。其次，为了缓解不同序列化方式所带来的偏差，本文提出了一种多视点融合策略，将不同视角下的形状预测融合在一起。再次，将RNN内核植入一个多尺度的自动关联（Auto-Context）方案中，以不断细化形状预测图的细节。与挑战前列腺超声图像广泛验证，我们的框架桥梁严重的边界不完整性，并取得了前列腺边界划定最佳性能相比，几个先进的方法。此外，我们的方法是一般的，可以扩展到其他医学图像分割任务，其中边界不完整是主要挑战之一。

##### URL
[https://arxiv.org/abs/1612.01655](https://arxiv.org/abs/1612.01655)

##### PDF
[https://arxiv.org/pdf/1612.01655](https://arxiv.org/pdf/1612.01655)

