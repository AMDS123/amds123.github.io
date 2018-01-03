---
layout: post
title: "Accelerating Deep Learning with Memcomputing"
date: 2018-01-01 21:27:11
categories: arXiv_AI
tags: arXiv_AI Deep_Learning Recognition
author: Haik Manukian, Fabio L. Traversa, Massimiliano Di Ventra
mathjax: true
---

* content
{:toc}

##### Abstract
Restricted Boltzmann machines (RBMs) and their extensions, often called "deep-belief networks", are very powerful neural networks that have found widespread applicability in the fields of machine learning and big data. The standard way to training these models resorts to an iterative unsupervised procedure based on Gibbs sampling, called "contrastive divergence", and additional supervised tuning via back-propagation. However, this procedure has been shown not to follow any gradient and can lead to suboptimal solutions. In this paper, we show a very efficient alternative to contrastive divergence by means of simulations of digital memcomputing machines (DMMs). We test our approach on pattern recognition using the standard MNIST data set of hand-written numbers. DMMs sample very effectively the vast phase space defined by the probability distribution of RBMs over the test sample inputs, and provide a very good approximation close to the optimum. This efficient search significantly reduces the number of generative pre-training iterations necessary to achieve a given level of accuracy in the MNIST data set, as well as a total performance gain over the traditional approaches. In fact, the acceleration of the pre-training achieved by simulating DMMs is comparable to, in number of iterations, the recently reported hardware application of the quantum annealing method on the same network and data set. Notably, however, DMMs perform far better than the reported quantum annealing results in terms of quality of the training. Our approach is agnostic about the connectivity of the network. Therefore, it can be extended to train full Boltzmann machines, and even deep networks at once.

##### Abstract (translated by Google)
受限玻尔兹曼机（RBMs）及其扩展通常被称为“深层信念网络”，它是非常强大的神经网络，已经在机器学习和大数据领域得到广泛的应用。训练这些模型的标准方法采用基于吉布斯采样的迭代无监督过程，称为“对比发散”，以及通过反向传播的附加监督调整。然而，这个过程已经被证明没有遵循任何梯度，并可能导致次优的解决方案。在本文中，我们通过模拟数字存储计算机（DMMs）展示了一种非常有效的对比分歧替代方案。我们使用手写数字的标准MNIST数据集来测试我们的模式识别方法。数字万用表非常有效地对由测试样本输入上的RBM的概率分布所定义的巨大相空间进行采样，并提供接近最佳值的非常好的近似值。这种有效的搜索显着减少了在MNIST数据集中达到给定准确度水平所需的生成预训练迭代次数，以及与传统方法相比的总体性能增益。实际上，通过模拟数字万用表实现的预先训练的加速度与最近报道的量子退火方法在同一网络和数据集上的硬件应用的迭代次数相当。然而值得注意的是，DMM在训练质量方面表现远优于报道的量子退火结果。我们的方法对于网络的连通性是不可知的。因此，它可以扩展到训练全玻尔兹曼机器，甚至一次深度网络。

##### URL
[http://arxiv.org/abs/1801.00512](http://arxiv.org/abs/1801.00512)

##### PDF
[http://arxiv.org/pdf/1801.00512](http://arxiv.org/pdf/1801.00512)

