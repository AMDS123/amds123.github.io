---
layout: post
title: "Deep Inception-Residual Laplacian Pyramid Networks for Accurate Single Image Super-Resolution"
date: 2017-11-15 07:04:30
categories: arXiv_CV
tags: arXiv_CV Super_Resolution CNN
author: Yongliang Tang, Weiguo Gong, Xi Chen, Weihong Li
mathjax: true
---

* content
{:toc}

##### Abstract
With exploiting contextual information over large image regions in an efficient way, the deep convolutional neural network has shown an impressive performance for single image super-resolution (SR). In this paper, we propose a deep convolutional network by cascading the well-designed inception-residual blocks within the deep Laplacian pyramid framework to progressively restore the missing high-frequency details of high-resolution (HR) images. By optimizing our network structure, the trainable depth of the proposed network gains a significant improvement, which in turn improves super-resolving accuracy. With our network depth increasing, however, the saturation and degradation of training accuracy continues to be a critical problem. As regard to this, we propose an effective two-stage training strategy, in which we firstly use images downsampled from the ground-truth HR images as the optimal objective to train the inception-residual blocks in each pyramid level with an extremely high learning rate enabled by gradient clipping, and then the ground-truth HR images are used to fine-tune all the pre-trained inception-residual blocks for obtaining the final SR model. Furthermore, we present a new loss function operating in both image space and local rank space to optimize our network for exploiting the contextual information among different output components. Extensive experiments on benchmark datasets validate that the proposed method outperforms existing state-of-the-art SR methods in terms of the objective evaluation as well as the visual quality.

##### Abstract (translated by Google)
通过高效地利用大图像区域的上下文信息，深卷积神经网络在单幅图像超分辨率（SR）方面表现出令人印象深刻的性能。在本文中，我们提出了一个深层卷积网络，通过层叠精心设计的深拉普拉斯金字塔框架内的初始残差块，逐步恢复缺失的高分辨率（HR）图像的高频细节。通过优化网络结构，提出的网络可训练深度得到显着改善，进而提高超分辨率的精度。然而，随着网络深度的增加，训练精度的饱和度和退化率仍然是一个关键问题。针对这个问题，我们提出了一个有效的两阶段训练策略，首先使用从地面真实HR图像下采样得到的图像作为最优目标，以极高的学习率训练每个金字塔水平的初始残差块然后利用地面真实HR图像对所有预先训练的初始残差块进行微调，得到最终的SR模型。此外，我们提出了在图像空间和局部秩空间中运行的新的损失函数，以优化我们的网络以利用不同输出组件之间的上下文信息。基准数据集的大量实验验证了所提出的方法在客观评估以及视觉质量方面优于现有的最新SR方法。

##### URL
[https://arxiv.org/abs/1711.05431](https://arxiv.org/abs/1711.05431)

##### PDF
[https://arxiv.org/pdf/1711.05431](https://arxiv.org/pdf/1711.05431)

