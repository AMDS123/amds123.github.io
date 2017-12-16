---
layout: post
title: "Probabilistic Neural Network with Complex Exponential Activation Functions in Image Recognition using Deep Learning Framework"
date: 2017-08-09 06:50:32
categories: arXiv_CV
tags: arXiv_CV Face CNN Transfer_Learning Classification Deep_Learning Recognition Face_Recognition
author: Andrey Savchenko
mathjax: true
---

* content
{:toc}

##### Abstract
If the training dataset is not very large, image recognition is usually implemented with the transfer learning methods. In these methods the features are extracted using a deep convolutional neural network, which was preliminarily trained with an external very-large dataset. In this paper we consider the nonparametric classification of extracted feature vectors with the probabilistic neural network (PNN). The number of neurons at the pattern layer of the PNN is equal to the database size, which causes the low recognition performance and high memory space complexity of this network. We propose to overcome these drawbacks by replacing the exponential activation function in the Gaussian Parzen kernel to the complex exponential functions in the Fej\'er kernel. We demonstrate that in this case it is possible to implement the network with the number of neurons in the pattern layer proportional to the cubic root of the database size. Thus, the proposed modification of the PNN makes it possible to significantly decrease runtime and memory complexities without loosing its main advantages, namely, extremely fast training procedure and the convergence to the optimal Bayesian decision. An experimental study in visual object category classification and unconstrained face recognition with contemporary deep neural networks have shown, that our approach obtains very efficient and rather accurate decisions for the small training sample in comparison with the well-known classifiers.

##### Abstract (translated by Google)
如果训练数据集不是很大，通常采用传递学习方法来实现图像识别。在这些方法中，使用深度卷积神经网络来提取特征，所述深度卷积神经网络用外部非常大的数据集进行初步训练。在本文中，我们考虑用概率神经网络（PNN）提取特征向量的非参数分类。 PNN模式层的神经元个数等于数据库的大小，导致该网络识别性能较差，存储空间复杂度较高。我们建议克服这些缺点，将高斯Parzen核中的指数激活函数替换成Fej核内的复指数函数。我们证明，在这种情况下，可以实现与数据库大小的立方根成正比的模式层中的神经元的数量的网络。因此，所提出的对PNN的修改使得可以显着减少运行时间和存储器的复杂度，而不失去其主要优点，即极快的训练过程和收敛到最优贝叶斯决策。在当代深度神经网络的视觉对象分类和无约束人脸识别实验研究表明，我们的方法获得了非常有效和相当准确的决定，与知名的分类器相比，小的训练样本。

##### URL
[https://arxiv.org/abs/1708.02733](https://arxiv.org/abs/1708.02733)

##### PDF
[https://arxiv.org/pdf/1708.02733](https://arxiv.org/pdf/1708.02733)

