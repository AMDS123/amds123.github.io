---
layout: post
title: "Model-based learning of local image features for unsupervised texture segmentation"
date: 2017-08-01 06:35:46
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Martin Kiechle, Martin Storath, Andreas Weinmann, Martin Kleinsteuber
mathjax: true
---

* content
{:toc}

##### Abstract
Features that capture well the textural patterns of a certain class of images are crucial for the performance of texture segmentation methods. The manual selection of features or designing new ones can be a tedious task. Therefore, it is desirable to automatically adapt the features to a certain image or class of images. Typically, this requires a large set of training images with similar textures and ground truth segmentation. In this work, we propose a framework to learn features for texture segmentation when no such training data is available. The cost function for our learning process is constructed to match a commonly used segmentation model, the piecewise constant Mumford-Shah model. This means that the features are learned such that they provide an approximately piecewise constant feature image with a small jump set. Based on this idea, we develop a two-stage algorithm which first learns suitable convolutional features and then performs a segmentation. We note that the features can be learned from a small set of images, from a single image, or even from image patches. The proposed method achieves a competitive rank in the Prague texture segmentation benchmark, and it is effective for segmenting histological images.

##### Abstract (translated by Google)
捕捉特定类别图像的纹理图案的特征对于纹理分割方法的性能是至关重要的。手动选择功能或设计新功能可能是一项繁琐的任务。因此，希望自动地将特征适应于特定的图像或图像类别。通常情况下，这需要大量具有相似纹理和地面真实分割的训练图像。在这项工作中，当没有这样的训练数据可用时，我们提出了一个学习纹理分割特征的框架。我们的学习过程的成本函数被构建为匹配常用的分段模型，分段常数Mumford-Shah模型。这意味着这些特征被学习，使得它们提供具有小跳跃集的近似分段恒定的特征图像。基于这个思想，我们开发了一个两阶段算法，首先学习合适的卷积特征，然后进行分割。我们注意到，这些特征可以从一小部分图像，单个图像，甚至图像补丁中学习。该方法在布拉格纹理分割基准测试中达到了较好的分类效果，对分割组织图像很有效。

##### URL
[https://arxiv.org/abs/1708.00180](https://arxiv.org/abs/1708.00180)

##### PDF
[https://arxiv.org/pdf/1708.00180](https://arxiv.org/pdf/1708.00180)

