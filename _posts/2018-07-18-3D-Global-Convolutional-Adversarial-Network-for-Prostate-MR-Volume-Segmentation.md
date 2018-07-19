---
layout: post
title: "3D Global Convolutional Adversarial Network for Prostate MR Volume Segmentation"
date: 2018-07-18 02:27:53
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation CNN Classification Deep_Learning Prediction
author: Haozhe Jia, Yang Song, Donghao Zhang, Heng Huang, Dagan Feng, Michael Fulham, Yong Xia, Weidong Cai
mathjax: true
---

* content
{:toc}

##### Abstract
Advanced deep learning methods have been developed to conduct prostate MR volume segmentation in either a 2D or 3D fully convolutional manner. However, 2D methods tend to have limited segmentation performance, since large amounts of spatial information of prostate volumes are discarded during the slice-by-slice segmentation process; and 3D methods also have room for improvement, since they use isotropic kernels to perform 3D convolutions whereas most prostate MR volumes have anisotropic spatial resolution. Besides, the fully convolutional structural methods achieve good performance for localization issues but neglect the per-voxel classification for segmentation tasks. In this paper, we propose a 3D Global Convolutional Adversarial Network (3D GCA-Net) to address efficient prostate MR volume segmentation. We first design a 3D ResNet encoder to extract 3D features from prostate scans, and then develop the decoder, which is composed of a multi-scale 3D global convolutional block and a 3D boundary refinement block, to address the classification and localization issues simultaneously for volumetric segmentation. Additionally, we combine the encoder-decoder segmentation network with an adversarial network in the training phrase to enforce the contiguity of long-range spatial predictions. Throughout the proposed model, we use anisotropic convolutional processing for better feature learning on prostate MR scans. We evaluated our 3D GCA-Net model on two public prostate MR datasets and achieved state-of-the-art performances.

##### Abstract (translated by Google)
已经开发了先进的深度学习方法以2D或3D完全卷积方式进行前列腺MR体积分割。然而，2D方法倾向于具有有限的分割性能，因为在逐个切片分割过程期间丢弃了前列腺体积的大量空间信息; 3D方法也有改进的余地，因为它们使用各向同性的核来执行3D卷积，而大多数前列腺MR体积具有各向异性的空间分辨率。此外，完全卷积结构方法在定位问题上取得了良好的性能，但忽略了分割任务的每体素分类。在本文中，我们提出了一个3D全球卷积对抗网络（3D GCA-Net）来解决有效的前列腺MR体积分割问题。我们首先设计3D ResNet编码器以从前列腺扫描中提取3D特征，然后开发解码器，其由多尺度3D全局卷积块和3D边界细化块组成，以同时解决体积分类和定位问题分割。此外，我们将编码器 - 解码器分段网络与训练短语中的对抗性网络相结合，以强制执行远程空间预测的连续性。在整个提出的模型中，我们使用各向异性卷积处理来更好地进行前列腺MR扫描的特征学习。我们在两个公共前列腺MR数据集上评估了我们的3D GCA-Net模型，并实现了最先进的性能。

##### URL
[https://arxiv.org/abs/1807.06742](https://arxiv.org/abs/1807.06742)

##### PDF
[https://arxiv.org/pdf/1807.06742](https://arxiv.org/pdf/1807.06742)

