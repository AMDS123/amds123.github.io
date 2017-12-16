---
layout: post
title: "Learning Multi-Scale Deep Features for High-Resolution Satellite Image Classification"
date: 2016-11-11 05:31:42
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification
author: Qingshan Liu, Renlong Hang, Huihui Song, Zhi Li
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a multi-scale deep feature learning method for high-resolution satellite image classification. Specifically, we firstly warp the original satellite image into multiple different scales. The images in each scale are employed to train a deep convolutional neural network (DCNN). However, simultaneously training multiple DCNNs is time-consuming. To address this issue, we explore DCNN with spatial pyramid pooling (SPP-net). Since different SPP-nets have the same number of parameters, which share the identical initial values, and only fine-tuning the parameters in fully-connected layers ensures the effectiveness of each network, thereby greatly accelerating the training process. Then, the multi-scale satellite images are fed into their corresponding SPP-nets respectively to extract multi-scale deep features. Finally, a multiple kernel learning method is developed to automatically learn the optimal combination of such features. Experiments on two difficult datasets show that the proposed method achieves favorable performance compared to other state-of-the-art methods.

##### Abstract (translated by Google)
本文提出了一种高分辨率卫星图像分类的多尺度深度特征学习方法。具体来说，我们首先将原始卫星图像变换成多个不同的尺度。采用各尺度的图像训练深度卷积神经网络（DCNN）。但是，同时训练多个DCNN是耗时的。为了解决这个问题，我们用空间金字塔池（SPP-net）来探索DCNN。由于不同的SPP网具有相同数量的参数，共享相同的初始值，只有在全连接层进行微调才能保证每个网络的有效性，从而大大加快训练过程。然后将多尺度卫星图像分别送入相应的SPP网络，提取多尺度深度特征。最后，开发了多核学习方法来自动学习这些特征的最佳组合。在两个困难的数据集上的实验表明，与其他最先进的方法相比，所提出的方法实现了良好的性能。

##### URL
[https://arxiv.org/abs/1611.03591](https://arxiv.org/abs/1611.03591)

##### PDF
[https://arxiv.org/pdf/1611.03591](https://arxiv.org/pdf/1611.03591)

