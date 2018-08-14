---
layout: post
title: "Semi-supervised Skin Lesion Segmentation via Transformation Consistent Self-ensembling Model"
date: 2018-08-12 03:57:29
categories: arXiv_CV
tags: arXiv_CV Regularization Segmentation Deep_Learning Prediction
author: Xiaomeng Li, Lequan Yu, Hao Chen, Chi-Wing Fu, Pheng-Ann Heng
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic skin lesion segmentation on dermoscopic images is an essential component in computer-aided diagnosis of melanoma. Recently, many fully supervised deep learning based methods have been proposed for automatic skin lesion segmentation. However, these approaches require massive pixel-wise annotation from experienced dermatologists, which is very costly and time-consuming. In this paper, we present a novel semi-supervised method for skin lesion segmentation by leveraging both labeled and unlabeled data. The network is optimized by the weighted combination of a common supervised loss for labeled inputs only and a regularization loss for both labeled and unlabeled data. In this paper, we present a novel semi-supervised method for skin lesion segmentation, where the network is optimized by the weighted combination of a common supervised loss for labeled inputs only and a regularization loss for both labeled and unlabeled data. Our method encourages a consistent prediction for unlabeled images using the outputs of the network-in-training under different regularizations, so that it can utilize the unlabeled data. To utilize the unlabeled data, our method encourages the consistent predictions of the network-in-training for the same input under different regularizations. Aiming for the semi-supervised segmentation problem, we enhance the effect of regularization for pixel-level predictions by introducing a transformation, including rotation and flipping, consistent scheme in our self-ensembling model. With only 300 labeled training samples, our method sets a new record on the benchmark of the International Skin Imaging Collaboration (ISIC) 2017 skin lesion segmentation challenge. Such a result clearly surpasses fully-supervised state-of-the-arts that are trained with 2000 labeled data.

##### Abstract (translated by Google)
皮肤镜图像上的自动皮肤病变分割是计算机辅助诊断黑素瘤的重要组成部分。最近，已经提出了许多用于自动皮肤病变分割的完全监督的基于深度学习的方法。然而，这些方法需要来自经验丰富的皮肤科医生的大量像素注释，这非常昂贵且耗时。在本文中，我们通过利用标记和未标记的数据，提出了一种新的半监督皮肤病变分割方法。通过仅标记输入的公共监督损失和标记和未标记数据的正则化损失的加权组合来优化网络。在本文中，我们提出了一种新的半监督皮肤病变分割方法，其中网络通过仅标记输入的共同监督损失和标记和未标记数据的正规化损失的加权组合来优化。我们的方法鼓励使用不同正则化下的训练网络的输出对未标记图像进行一致预测，以便它可以利用未标记的数据。为了利用未标记的数据，我们的方法鼓励在不同的正则化下对相同输入的训练网络进行一致的预测。针对半监督分割问题，我们通过在自我集成模型中引入包括旋转和翻转，一致方案的变换来增强正则化对像素级预测的影响。我们的方法只有300个标记的训练样本，在国际皮肤影像协作（ISIC）2017皮肤病变分割挑战的基准上创下了新记录。这样的结果显然超过了用2000标记数据训练的完全监督的现有技术。

##### URL
[http://arxiv.org/abs/1808.03887](http://arxiv.org/abs/1808.03887)

##### PDF
[http://arxiv.org/pdf/1808.03887](http://arxiv.org/pdf/1808.03887)

