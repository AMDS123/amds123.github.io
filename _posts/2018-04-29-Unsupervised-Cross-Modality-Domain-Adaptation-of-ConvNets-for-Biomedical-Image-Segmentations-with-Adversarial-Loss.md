---
layout: post
title: "Unsupervised Cross-Modality Domain Adaptation of ConvNets for Biomedical Image Segmentations with Adversarial Loss"
date: 2018-04-29 12:19:53
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation CNN Transfer_Learning Prediction
author: Qi Dou, Cheng Ouyang, Cheng Chen, Hao Chen, Pheng-Ann Heng
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional networks (ConvNets) have achieved great successes in various challenging vision tasks. However, the performance of ConvNets would degrade when encountering the domain shift. The domain adaptation is more significant while challenging in the field of biomedical image analysis, where cross-modality data have largely different distributions. Given that annotating the medical data is especially expensive, the supervised transfer learning approaches are not quite optimal. In this paper, we propose an unsupervised domain adaptation framework with adversarial learning for cross-modality biomedical image segmentations. Specifically, our model is based on a dilated fully convolutional network for pixel-wise prediction. Moreover, we build a plug-and-play domain adaptation module (DAM) to map the target input to features which are aligned with source domain feature space. A domain critic module (DCM) is set up for discriminating the feature space of both domains. We optimize the DAM and DCM via an adversarial loss without using any target domain label. Our proposed method is validated by adapting a ConvNet trained with MRI images to unpaired CT data for cardiac structures segmentations, and achieved very promising results.

##### Abstract (translated by Google)
卷积网络（ConvNets）在各种具有挑战性的视觉任务中取得了巨大成功。但是，遇到域名转移时，ConvNets的性能会降低。在生物医学图像分析领域，跨领域数据具有大不相同的分布，领域适应更具有挑战性。鉴于对医疗数据进行注释特别昂贵，有监督的转移学习方法并不十分理想。在本文中，我们提出了一个无监督的领域适应框架与敌对学习跨模态生物医学图像分割。具体来说，我们的模型是基于扩展完全卷积网络的像素级预测。此外，我们构建了即插即用域自适应模块（DAM），将目标输入映射到与源域特征空间对齐的要素。域批评模块（DCM）用于区分两个域的特征空间。我们通过敌对损失优化DAM和DCM，而不使用任何目标域标签。我们所提出的方法通过将用MRI图像训练的ConvNet调整为用于心脏结构分割的未配对CT数据来验证，并且获得了非常有希望的结果。

##### URL
[https://arxiv.org/abs/1804.10916](https://arxiv.org/abs/1804.10916)

##### PDF
[https://arxiv.org/pdf/1804.10916](https://arxiv.org/pdf/1804.10916)

