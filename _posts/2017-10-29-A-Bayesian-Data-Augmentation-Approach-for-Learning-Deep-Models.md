---
layout: post
title: "A Bayesian Data Augmentation Approach for Learning Deep Models"
date: 2017-10-29 05:02:14
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Classification Deep_Learning
author: Toan Tran, Trung Pham, Gustavo Carneiro, Lyle Palmer, Ian Reid
mathjax: true
---

* content
{:toc}

##### Abstract
Data augmentation is an essential part of the training process applied to deep learning models. The motivation is that a robust training process for deep learning models depends on large annotated datasets, which are expensive to be acquired, stored and processed. Therefore a reasonable alternative is to be able to automatically generate new annotated training samples using a process known as data augmentation. The dominant data augmentation approach in the field assumes that new training samples can be obtained via random geometric or appearance transformations applied to annotated training samples, but this is a strong assumption because it is unclear if this is a reliable generative model for producing new training samples. In this paper, we provide a novel Bayesian formulation to data augmentation, where new annotated training points are treated as missing variables and generated based on the distribution learned from the training set. For learning, we introduce a theoretically sound algorithm --- generalised Monte Carlo expectation maximisation, and demonstrate one possible implementation via an extension of the Generative Adversarial Network (GAN). Classification results on MNIST, CIFAR-10 and CIFAR-100 show the better performance of our proposed method compared to the current dominant data augmentation approach mentioned above --- the results also show that our approach produces better classification results than similar GAN models.

##### Abstract (translated by Google)
数据增强是应用于深度学习模型的培训过程的重要组成部分。其动机是深度学习模型的强大的训练过程取决于大的注释数据集，这些数据集被获取，存储和处理是昂贵的。因此，合理的选择是能够使用称为数据增强的过程来自动生成新的注释的训练样本。本领域的主要数据增强方法假定可以通过对注释训练样本进行随机几何或外观变换来获得新的训练样本，但是这是一个强有力的假设，因为不清楚这是否是用于产生新训练样本的可靠生成模型。在本文中，我们提供了一种新的贝叶斯公式的数据增强，其中新的注释的训练点被视为缺失变量，并根据从训练集中学习的分布生成。为了学习，我们引入了一个理论上合理的算法---广义蒙特卡罗期望最大化，并通过对生成对手网络（GAN）的扩展来演示一个可能的实现。 MNIST，CIFAR-10和CIFAR-100的分类结果表明，与目前的主导数据增强方法相比，我们提出的方法具有更好的性能 - 结果也表明，我们的方法比类似的GAN模型产生更好的分类结果。

##### URL
[https://arxiv.org/abs/1710.10564](https://arxiv.org/abs/1710.10564)

##### PDF
[https://arxiv.org/pdf/1710.10564](https://arxiv.org/pdf/1710.10564)

