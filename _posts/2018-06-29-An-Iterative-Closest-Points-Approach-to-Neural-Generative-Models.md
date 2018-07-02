---
layout: post
title: "An Iterative Closest Points Approach to Neural Generative Models"
date: 2018-06-29 15:21:40
categories: arXiv_AI
tags: arXiv_AI
author: Joose Rajam&#xe4;ki, Perttu H&#xe4;m&#xe4;l&#xe4;inen
mathjax: true
---

* content
{:toc}

##### Abstract
We present a simple way to learn a transformation that maps samples of one distribution to the samples of another distribution. Our algorithm comprises an iteration of 1) drawing samples from some simple distribution and transforming them using a neural network, 2) determining pairwise correspondences between the transformed samples and training data (or a minibatch), and 3) optimizing the weights of the neural network being trained to minimize the distances between the corresponding vectors. This can be considered as a variant of the Iterative Closest Points (ICP) algorithm, common in geometric computer vision, although ICP typically operates on sensor point clouds and linear transforms instead of random sample sets and neural nonlinear transforms. We demonstrate the algorithm on simple synthetic data and MNIST data. We furthermore demonstrate that the algorithm is capable of handling distributions with both continuous and discrete variables.

##### Abstract (translated by Google)
我们提出了一种简单的方法来学习将一个分布的样本映射到另一个分布的样本的转换。我们的算法包括以下迭代：1）从一些简单分布中抽取样本并使用神经网络对其进行变换; 2）确定变换样本与训练数据（或小批次）之间的成对对应关系; 3）优化神经网络的权重被训练以最小化相应向量之间的距离。尽管ICP通常在传感器点云和线性变换上运行，而不是随机样本集和神经元非线性变换，但这可以视为迭代最接近点（ICP）算法的变体，这在几何计算机视觉中很常见。我们演示简单的合成数据和MNIST数据的算法。我们进一步证明该算法能够处理具有连续和离散变量的分布。

##### URL
[http://arxiv.org/abs/1711.06562](http://arxiv.org/abs/1711.06562)

##### PDF
[http://arxiv.org/pdf/1711.06562](http://arxiv.org/pdf/1711.06562)

