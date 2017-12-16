---
layout: post
title: "Deep Collaborative Learning for Visual Recognition"
date: 2017-03-03 16:17:45
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification Recognition
author: Yan Wang, Lingxi Xie, Ya Zhang, Wenjun Zhang, Alan Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks are playing an important role in state-of-the-art visual recognition. To represent high-level visual concepts, modern networks are equipped with large convolutional layers, which use a large number of filters and contribute significantly to model complexity. For example, more than half of the weights of AlexNet are stored in the first fully-connected layer (4,096 filters). We formulate the function of a convolutional layer as learning a large visual vocabulary, and propose an alternative way, namely Deep Collaborative Learning (DCL), to reduce the computational complexity. We replace a convolutional layer with a two-stage DCL module, in which we first construct a couple of smaller convolutional layers individually, and then fuse them at each spatial position to consider feature co-occurrence. In mathematics, DCL can be explained as an efficient way of learning compositional visual concepts, in which the vocabulary size increases exponentially while the model complexity only increases linearly. We evaluate DCL on a wide range of visual recognition tasks, including a series of multi-digit number classification datasets, and some generic image classification datasets such as SVHN, CIFAR and ILSVRC2012. We apply DCL to several state-of-the-art network structures, improving the recognition accuracy meanwhile reducing the number of parameters (16.82% fewer in AlexNet).

##### Abstract (translated by Google)
深度神经网络在最先进的视觉识别中发挥着重要的作用。为了表示高层次的视觉概念，现代网络配备了大量的卷积层，这些层使用大量的过滤器，并且对模型的复杂性有很大的贡献。例如，超过一半的AlexNet权重存储在第一个完全连接层（4,096个过滤器）中。我们将卷积层的功能定义为学习大量的视觉词汇，并提出了另一种方法，即深度协作学习（DCL），以降低计算复杂度。我们用一个两阶段的DCL模块替换卷积层，在这个模块中我们首先单独构造一些较小的卷积层，然后在每个空间位置融合它们以考虑特征共现。在数学中，DCL可以被解释为一种学习构图视觉概念的有效方式，其中词汇大小呈指数增长，而模型复杂度仅仅线性增加。我们评估DCL的广泛的视觉识别任务，包括一系列的多位数字分类数据集，以及一些通用的图像分类数据集，如SVHN，CIFAR和ILSVRC2012。我们将DCL应用于多个最先进的网络结构，提高了识别的准确性，同时减少了参数数量（在AlexNet中减少了16.82％）。

##### URL
[https://arxiv.org/abs/1703.01229](https://arxiv.org/abs/1703.01229)

##### PDF
[https://arxiv.org/pdf/1703.01229](https://arxiv.org/pdf/1703.01229)

