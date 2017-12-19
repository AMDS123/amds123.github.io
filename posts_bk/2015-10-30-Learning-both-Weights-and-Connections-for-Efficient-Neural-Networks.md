---
layout: post
title: "Learning both Weights and Connections for Efficient Neural Networks"
date: 2015-10-30 23:29:27
categories: arXiv_CV
tags: arXiv_CV
author: Song Han, Jeff Pool, John Tran, William J. Dally
mathjax: true
---

* content
{:toc}

##### Abstract
Neural networks are both computationally intensive and memory intensive, making them difficult to deploy on embedded systems. Also, conventional networks fix the architecture before training starts; as a result, training cannot improve the architecture. To address these limitations, we describe a method to reduce the storage and computation required by neural networks by an order of magnitude without affecting their accuracy by learning only the important connections. Our method prunes redundant connections using a three-step method. First, we train the network to learn which connections are important. Next, we prune the unimportant connections. Finally, we retrain the network to fine tune the weights of the remaining connections. On the ImageNet dataset, our method reduced the number of parameters of AlexNet by a factor of 9x, from 61 million to 6.7 million, without incurring accuracy loss. Similar experiments with VGG-16 found that the number of parameters can be reduced by 13x, from 138 million to 10.3 million, again with no loss of accuracy.

##### Abstract (translated by Google)
神经网络既是计算密集型又是内存密集型的，使得它们难以在嵌入式系统上部署。而且，传统网络在训练开始之前修复了架构;因此，培训不能改善建筑。为了解决这些限制，我们描述了一种方法来减少神经网络所需的存储和计算一个数量级，而不影响它们的准确性，只学习重要的连接。我们的方法使用三步法修剪冗余连接。首先，我们训练网络来了解哪些连接是重要的。接下来，我们修剪不重要的连接。最后，我们重新训练网络来微调其余连接的权重。在ImageNet数据集上，我们的方法将AlexNet的参数数量减少了9倍，从6,100万减少到6,7百万，而不会造成精度损失。与VGG-16类似的实验发现，参数的数量可以减少13倍，从1.38亿减少到1030万，而且不会降低精度。

##### URL
[https://arxiv.org/abs/1506.02626](https://arxiv.org/abs/1506.02626)

##### PDF
[https://arxiv.org/pdf/1506.02626](https://arxiv.org/pdf/1506.02626)

