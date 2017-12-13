---
layout: post
title: "Memory Bounded Deep Convolutional Networks"
date: 2014-12-03 19:08:38
categories: arXiv_CV
tags: arXiv_CV Regularization Sparse CNN Gradient_Descent
author: Maxwell D. Collins, Pushmeet Kohli
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we investigate the use of sparsity-inducing regularizers during training of Convolution Neural Networks (CNNs). These regularizers encourage that fewer connections in the convolution and fully connected layers take non-zero values and in effect result in sparse connectivity between hidden units in the deep network. This in turn reduces the memory and runtime cost involved in deploying the learned CNNs. We show that training with such regularization can still be performed using stochastic gradient descent implying that it can be used easily in existing codebases. Experimental evaluation of our approach on MNIST, CIFAR, and ImageNet datasets shows that our regularizers can result in dramatic reductions in memory requirements. For instance, when applied on AlexNet, our method can reduce the memory consumption by a factor of four with minimal loss in accuracy.

##### Abstract (translated by Google)
在这项工作中，我们调查卷积神经网络（CNNs）的培训期间使用稀疏诱导正规化。这些正规化器鼓励在卷积和完全连接的层中较少的连接采用非零值，并且实际上导致深度网络中隐藏单元之间的稀疏连接。这又降低了部署所学习的CNN所涉及的存储器和运行时间成本。我们表明，这种正则化训练仍然可以使用随机梯度下降来进行，这意味着它可以很容易地在现有的代码库中使用。我们对MNIST，CIFAR和ImageNet数据集的方法的实验评估表明，我们的正规化器可以显着降低内存需求。例如，在AlexNet上应用时，我们的方法可以将内存消耗减少四分之一，同时精确度损失最小。

##### URL
[https://arxiv.org/abs/1412.1442](https://arxiv.org/abs/1412.1442)

##### PDF
[https://arxiv.org/pdf/1412.1442](https://arxiv.org/pdf/1412.1442)

