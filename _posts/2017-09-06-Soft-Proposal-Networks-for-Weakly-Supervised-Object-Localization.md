---
layout: post
title: "Soft Proposal Networks for Weakly Supervised Object Localization"
date: 2017-09-06 14:11:59
categories: arXiv_CV
tags: arXiv_CV Knowledge Weakly_Supervised CNN Optimization Classification
author: Yi Zhu, Yanzhao Zhou, Qixiang Ye, Qiang Qiu, Jianbin Jiao
mathjax: true
---

* content
{:toc}

##### Abstract
Weakly supervised object localization remains challenging, where only image labels instead of bounding boxes are available during training. Object proposal is an effective component in localization, but often computationally expensive and incapable of joint optimization with some of the remaining modules. In this paper, to the best of our knowledge, we for the first time integrate weakly supervised object proposal into convolutional neural networks (CNNs) in an end-to-end learning manner. We design a network component, Soft Proposal (SP), to be plugged into any standard convolutional architecture to introduce the nearly cost-free object proposal, orders of magnitude faster than state-of-the-art methods. In the SP-augmented CNNs, referred to as Soft Proposal Networks (SPNs), iteratively evolved object proposals are generated based on the deep feature maps then projected back, and further jointly optimized with network parameters, with image-level supervision only. Through the unified learning process, SPNs learn better object-centric filters, discover more discriminative visual evidence, and suppress background interference, significantly boosting both weakly supervised object localization and classification performance. We report the best results on popular benchmarks, including PASCAL VOC, MS COCO, and ImageNet.

##### Abstract (translated by Google)
弱监督的对象本地化仍然具有挑战性，在训练期间只有图像标签而不是边界框可用。对象建议是本地化中的一个有效组件，但通常在计算上昂贵且无法与其余一些模块进行联合优化。在本文中，就我们所知，我们首次将弱监督对象建议以端到端的学习方式整合到卷积神经网络（CNN）中。我们设计了一个网络组件Soft Proposal（SP），插入到任何标准的卷积体系结构中，以引入几乎免费的对象建议，比现有技术的方法快几个数量级。在被称为软提议网络（SPN）的SP增强CNN中，基于深度特征映射然后被投影回来生成迭代演进的对象提议，并且进一步与网络参数一起进行联合优化，仅具有图像级监督。通过统一的学习过程，SPN学习了更好的以对象为中心的过滤器，发现更具辨别性的视觉证据，并抑制背景干扰，显着提升弱监督对象定位和分类性能。我们在流行的基准测试中报告了最好的结果，包括PASCAL VOC，MS COCO和ImageNet。

##### URL
[https://arxiv.org/abs/1709.01829](https://arxiv.org/abs/1709.01829)

##### PDF
[https://arxiv.org/pdf/1709.01829](https://arxiv.org/pdf/1709.01829)

