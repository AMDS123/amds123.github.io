---
layout: post
title: "Understanding data augmentation for classification: when to warp?"
date: 2016-11-26 11:08:19
categories: arXiv_CV
tags: arXiv_CV CNN Classification
author: Sebastien C. Wong, Adam Gatt, Victor Stamatescu, Mark D. McDonnell
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we investigate the benefit of augmenting data with synthetically created samples when training a machine learning classifier. Two approaches for creating additional training samples are data warping, which generates additional samples through transformations applied in the data-space, and synthetic over-sampling, which creates additional samples in feature-space. We experimentally evaluate the benefits of data augmentation for a convolutional backpropagation-trained neural network, a convolutional support vector machine and a convolutional extreme learning machine classifier, using the standard MNIST handwritten digit dataset. We found that while it is possible to perform generic augmentation in feature-space, if plausible transforms for the data are known then augmentation in data-space provides a greater benefit for improving performance and reducing overfitting.

##### Abstract (translated by Google)
在本文中，我们调查了在训练机器学习分类器时利用合成创建的样本来增加数据的好处。创建额外训练样本的两种方法是数据规整，通过在数据空间中应用转换生成附加样本，以及在特征空间中创建附加样本的合成过采样。我们用标准MNIST手写数字数据集实验评估了卷积反向传播训练的神经网络，卷积支持向量机和卷积极限学习机分类器的数据增强的好处。我们发现尽管可以在特征空间中执行泛型增强，但是如果知道数据的合理变换，那么数据空间中的增强为改善性能和减少过度拟合提供了更大的益处。

##### URL
[https://arxiv.org/abs/1609.08764](https://arxiv.org/abs/1609.08764)

##### PDF
[https://arxiv.org/pdf/1609.08764](https://arxiv.org/pdf/1609.08764)

