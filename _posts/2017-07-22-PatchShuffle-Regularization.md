---
layout: post
title: "PatchShuffle Regularization"
date: 2017-07-22 04:33:02
categories: arXiv_CV
tags: arXiv_CV Regularization Image_Generation CNN Classification
author: Guoliang Kang, Xuanyi Dong, Liang Zheng, Yi Yang
mathjax: true
---

* content
{:toc}

##### Abstract
This paper focuses on regularizing the training of the convolutional neural network (CNN). We propose a new regularization approach named ``PatchShuffle`` that can be adopted in any classification-oriented CNN models. It is easy to implement: in each mini-batch, images or feature maps are randomly chosen to undergo a transformation such that pixels within each local patch are shuffled. Through generating images and feature maps with interior orderless patches, PatchShuffle creates rich local variations, reduces the risk of network overfitting, and can be viewed as a beneficial supplement to various kinds of training regularization techniques, such as weight decay, model ensemble and dropout. Experiments on four representative classification datasets show that PatchShuffle improves the generalization ability of CNN especially when the data is scarce. Moreover, we empirically illustrate that CNN models trained with PatchShuffle are more robust to noise and local changes in an image.

##### Abstract (translated by Google)
本文重点研究了卷积神经网络（CNN）的训练。我们提出了一种名为“PatchShuffle”的新的正则化方法，可以在任何面向分类的CNN模型中采用。这很容易实现：在每个小批量中，随机选择图像或特征映射进行转换，使得每个局部区块内的像素被混洗。通过生成具有内部无序补丁的图像和特征映射，PatchShuffle创建丰富的局部变化，降低了网络过度拟合的风险，并且可以被视为对各种训练正则化技术（如体重衰减，模型集合和辍学）的有益补充。对4个代表性分类数据集的实验表明，PatchShuffle提高了CNN的泛化能力，特别是在数据稀缺的情况下。此外，我们经验性地说明，使用PatchShuffle训练的CNN模型对图像中的噪声和局部变化更加鲁棒。

##### URL
[https://arxiv.org/abs/1707.07103](https://arxiv.org/abs/1707.07103)

##### PDF
[https://arxiv.org/pdf/1707.07103](https://arxiv.org/pdf/1707.07103)

