---
layout: post
title:  Leaf Identification Using a Deep Convolutional Neural Network
date:   2017-12-05 18:20:05
categories: CV
tags: CV
author: Christoph Wick, Frank Puppe
---

* content
{:toc}

##### Abstract
Convolutional neural networks (CNNs) have become popular especially in computer vision in the last few years because they achieved outstanding performance on different tasks, such as image classifications. We propose a nine-layer CNN for leaf identification using the famous Flavia and Foliage datasets. Usually the supervised learning of deep CNNs requires huge datasets for training. However, the used datasets contain only a few examples per plant species. Therefore, we apply data augmentation and transfer learning to prevent our network from overfitting. The trained CNNs achieve recognition rates above 99% on the Flavia and Foliage datasets, and slightly outperform current methods for leaf classification.

##### Abstract (translated by Google)
卷积神经网络（CNNs）在过去的几年中，尤其是在计算机视觉领域已经变得非常流行，因为它们在图像分类等不同的任务上取得了出色的表现。我们提出了一个使用着名的Flavia和Foliage数据集的九层CNN叶识别。通常，深度CNN的监督式学习需要庞大的训练数据集。但是，使用的数据集仅包含每个植物物种的几个例子。因此，我们应用数据增强和转移学习来防止我们的网络过度配合。经过训练的CNN在Flavia和Foliage数据集上的识别率达到了99％以上，略好于目前的叶分类方法。

