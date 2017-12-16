---
layout: post
title: "Convolutional Neural Networks and Data Augmentation for Spectral-Spatial Classification of Hyperspectral Images"
date: 2017-11-15 12:02:57
categories: arXiv_CV
tags: arXiv_CV CNN Classification
author: Jacopo Acquarelli, Elena Marchiori, Lutgarde M.C. Buydens, Thanh Tran, Twan van Laarhoven
mathjax: true
---

* content
{:toc}

##### Abstract
Spectral-spatial classification of remotely sensed hyperspectral images has been the subject of many studies in recent years. Current methods achieve excellent performance on benchmark hyperspectral image labeling tasks when a sufficient number of labeled pixels is available. However, in the presence of only very few labeled pixels, such classification becomes a challenging problem. In this paper we propose to tackle this problem using convolutional neural networks (CNNs) and data augmentation. Our newly developed method relies on the assumption of spectral-spatial locality: nearby pixels in a hyperspectral image are related, in the sense that their spectra and their labels are likely to be similar. We exploit this assumption to develop 1) a new data augmentation procedure which adds new samples to the train set and 2) a tailored loss function which penalize differences among weights of the network corresponding to nearby wavelengths of the spectra. We train a simple single layer convolutional neural network with this loss function and augmented train set and use it to classify all unlabeled pixels of the given image. To assess the efficacy of our method, we used five publicly available hyperspectral images: Pavia Center, Pavia University, KSC, Indian Pines and Salina. On these images our method significantly outperforms other baselines. Notably, with just 1% of labeled pixels per class, on these dataset our method achieves an accuracy of 99.5%, etc. Furthermore we show that our method improves over other baselines also in a supervised setting, when no overlap between train and test pixels is allowed. Overall our investigation demonstrates that spectral-spatial locality can be easily embedded in a simple convolutional neural network through data augmentation and a tailored loss function.

##### Abstract (translated by Google)
遥感高光谱图像的光谱空间分类近年来一直是许多研究的主题。当有足够数量的标记像素可用时，当前的方法在基准高光谱图像标记任务上实现优异的性能。然而，在只有非常少的标记像素的情况下，这种分类成为具有挑战性的问题。在本文中，我们建议使用卷积神经网络（CNN）和数据增强来解决这个问题。我们新开发的方法依赖于光谱空间局部性的假设：高光谱图像中的附近像素是相关的，因为它们的光谱和它们的标记可能是相似的。我们利用这个假设来开发1）新的数据增加过程，其向火车组添加新的样本，以及2）定制的损失函数，其惩罚与邻近波长的频谱对应的网络的权重之间的差异。我们训练一个简单的单层卷积神经网络与这个损失函数和增广训练集，并用它来分类给定图像的所有未标记像素。为了评估我们的方法的有效性，我们使用了五个公开可用的高光谱图像：帕维亚中心，帕维亚大学，KSC，印度松树和萨利纳。在这些图像上，我们的方法明显优于其他基线。值得注意的是，每类只有1％的标记像素，在这些数据集上，我们的方法可以达到99.5％的精确度等等。此外，我们的方法还表明，在训练和测试像素之间没有重叠的情况下，被允许。总体而言，我们的调查表明，频谱空间局部性可以通过数据增强和量身定制的损失函数轻松嵌入简单的卷积神经网络。

##### URL
[https://arxiv.org/abs/1711.05512](https://arxiv.org/abs/1711.05512)

##### PDF
[https://arxiv.org/pdf/1711.05512](https://arxiv.org/pdf/1711.05512)

