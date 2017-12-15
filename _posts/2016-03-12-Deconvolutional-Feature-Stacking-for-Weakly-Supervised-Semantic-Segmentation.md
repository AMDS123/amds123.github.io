---
layout: post
title: "Deconvolutional Feature Stacking for Weakly-Supervised Semantic Segmentation"
date: 2016-03-12 08:22:30
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Inference
author: Hyo-Eun Kim, Sangheum Hwang
mathjax: true
---

* content
{:toc}

##### Abstract
A weakly-supervised semantic segmentation framework with a tied deconvolutional neural network is presented. Each deconvolution layer in the framework consists of unpooling and deconvolution operations. 'Unpooling' upsamples the input feature map based on unpooling switches defined by corresponding convolution layer's pooling operation. 'Deconvolution' convolves the input unpooled features by using convolutional weights tied with the corresponding convolution layer's convolution operation. The unpooling-deconvolution combination helps to eliminate less discriminative features in a feature extraction stage, since output features of the deconvolution layer are reconstructed from the most discriminative unpooled features instead of the raw one. This results in reduction of false positives in a pixel-level inference stage. All the feature maps restored from the entire deconvolution layers can constitute a rich discriminative feature set according to different abstraction levels. Those features are stacked to be selectively used for generating class-specific activation maps. Under the weak supervision (image-level labels), the proposed framework shows promising results on lesion segmentation in medical images (chest X-rays) and achieves state-of-the-art performance on the PASCAL VOC segmentation dataset in the same experimental condition.

##### Abstract (translated by Google)
提出了一种带有绑定反卷积神经网络的弱监督语义分割框架。框架中的每个解卷积层都包含解卷积和解卷积操作。 “解除合并”根据由相应的卷积层池操作定义的解除开关来上采样输入特征映射。 “反卷积”通过使用与相应的卷积层的卷积操作相关联的卷积加权来卷积输入的未卷积特征。解卷积组合有助于在特征提取阶段消除较少的区分特征，因为解卷积层的输出特征是从最具判别力的未混合特征重构而不是原始特征。这导致在像素级推断阶段减少误报。从整个反褶积层恢复的所有特征映射可以根据不同的抽象层次构成丰富的判别特征集。这些特征被堆叠以有选择地用于生成类别特定的激活图。在弱监督下（图像级标签），所提出的框架在医学图像（胸部X射线）的病灶分割中显示出有希望的结果，并且在相同实验条件下在PASCAL VOC分割数据集上实现了最新的性能。

##### URL
[https://arxiv.org/abs/1602.04984](https://arxiv.org/abs/1602.04984)

##### PDF
[https://arxiv.org/pdf/1602.04984](https://arxiv.org/pdf/1602.04984)

