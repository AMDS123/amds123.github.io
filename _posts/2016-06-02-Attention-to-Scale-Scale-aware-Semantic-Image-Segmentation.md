---
layout: post
title: "Attention to Scale: Scale-aware Semantic Image Segmentation"
date: 2016-06-02 02:02:21
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention CNN Classification
author: Liang-Chieh Chen, Yi Yang, Jiang Wang, Wei Xu, Alan L. Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
Incorporating multi-scale features in fully convolutional neural networks (FCNs) has been a key element to achieving state-of-the-art performance on semantic image segmentation. One common way to extract multi-scale features is to feed multiple resized input images to a shared deep network and then merge the resulting features for pixelwise classification. In this work, we propose an attention mechanism that learns to softly weight the multi-scale features at each pixel location. We adapt a state-of-the-art semantic image segmentation model, which we jointly train with multi-scale input images and the attention model. The proposed attention model not only outperforms average- and max-pooling, but allows us to diagnostically visualize the importance of features at different positions and scales. Moreover, we show that adding extra supervision to the output at each scale is essential to achieving excellent performance when merging multi-scale features. We demonstrate the effectiveness of our model with extensive experiments on three challenging datasets, including PASCAL-Person-Part, PASCAL VOC 2012 and a subset of MS-COCO 2014.

##### Abstract (translated by Google)
在完全卷积神经网络（FCN）中引入多尺度特征一直是实现语义图像分割的最新性能的关键要素。提取多尺度特征的一种常见方法是将多个调整大小的输入图像馈送到共享的深度网络，然后合并所得的特征以进行按像素分类。在这项工作中，我们提出了一个关注机制，学习轻轻地加权每个像素位置的多尺度特征。我们采用了先进的语义图像分割模型，我们通过多尺度的输入图像和注意模型进行联合训练。所提出的关注模型不仅胜过平均和最大集中，而且允许我们在不同位置和尺度上诊断性地显示特征的重要性。此外，我们还表明，在合并多尺度特征时，为了获得优异的性能，在每个尺度上增加对输出的额外监督是必不可少的。我们在三个具有挑战性的数据集上展示了我们的模型的有效性，包括PASCAL-Person-Part，PASCAL VOC 2012和MS-COCO 2014的子集。

##### URL
[https://arxiv.org/abs/1511.03339](https://arxiv.org/abs/1511.03339)

##### PDF
[https://arxiv.org/pdf/1511.03339](https://arxiv.org/pdf/1511.03339)

