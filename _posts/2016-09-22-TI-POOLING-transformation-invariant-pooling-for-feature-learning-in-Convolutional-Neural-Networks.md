---
layout: post
title: "TI-POOLING: transformation-invariant pooling for feature learning in Convolutional Neural Networks"
date: 2016-09-22 14:42:28
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN
author: Dmitry Laptev, Nikolay Savinov, Joachim M. Buhmann, Marc Pollefeys
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we present a deep neural network topology that incorporates a simple to implement transformation invariant pooling operator (TI-POOLING). This operator is able to efficiently handle prior knowledge on nuisance variations in the data, such as rotation or scale changes. Most current methods usually make use of dataset augmentation to address this issue, but this requires larger number of model parameters and more training data, and results in significantly increased training time and larger chance of under- or overfitting. The main reason for these drawbacks is that the learned model needs to capture adequate features for all the possible transformations of the input. On the other hand, we formulate features in convolutional neural networks to be transformation-invariant. We achieve that using parallel siamese architectures for the considered transformation set and applying the TI-POOLING operator on their outputs before the fully-connected layers. We show that this topology internally finds the most optimal "canonical" instance of the input image for training and therefore limits the redundancy in learned features. This more efficient use of training data results in better performance on popular benchmark datasets with smaller number of parameters when comparing to standard convolutional neural networks with dataset augmentation and to other baselines.

##### Abstract (translated by Google)
在本文中，我们提出了一个深度神经网络拓扑结合了一个简单的实现变换不变池操作（TI-POOLING）。该操作员能够有效地处理关于数据中的滋扰变化的先前知识，例如旋转或尺度变化。目前大多数方法通常使用数据集增强来解决这个问题，但是这需要大量的模型参数和更多的训练数据，并且导致训练时间显着增加以及较差或过度拟合的可能性较大。这些缺点的主要原因是学习模型需要捕获输入所有可能转换的足够特征。另一方面，我们将卷积神经网络中的特征制定为变换不变式。我们为所考虑的转换集合使用并行连体架构，并在完全连接的层之前在其输出上应用TI-POOLING运算符。我们表明，这种拓扑结构内部找到训练的输入图像的最佳“规范”实例，因此限制了学习功能的冗余。与具有数据集增强的标准卷积神经网络以及其他基线相比，这种更有效的训练数据的使用导致在具有较少参数的流行的基准数据集上具有更好的性能。

##### URL
[https://arxiv.org/abs/1604.06318](https://arxiv.org/abs/1604.06318)

##### PDF
[https://arxiv.org/pdf/1604.06318](https://arxiv.org/pdf/1604.06318)

