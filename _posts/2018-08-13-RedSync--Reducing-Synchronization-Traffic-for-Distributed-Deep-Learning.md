---
layout: post
title: "RedSync : Reducing Synchronization Traffic for Distributed Deep Learning"
date: 2018-08-13 19:02:47
categories: arXiv_CV
tags: arXiv_CV Attention Image_Classification Optimization Classification Deep_Learning Language_Model
author: Jiarui Fang, Haohuan Fu, Guangwen Yang, Cho-Jui Hsieh
mathjax: true
---

* content
{:toc}

##### Abstract
Data parallelism has already become a dominant method to scale Deep Neural Network (DNN) training to multiple computation nodes. Considering that the synchronization of local model or gradient between iterations can be a bottleneck for large-scale distributed training, compressing communication traffic has gained widespread attention recently. Among several recent proposed compression algorithms, Residual Gradient Compression (RGC) is one of the most successful approaches---it can significantly compress the message size (0.1% of the original size) and still preserve accuracy. However, the literature on compressing deep networks focuses almost exclusively on finding good compression rate, while the efficiency of RGC in real implementation has been less investigated. In this paper, we explore the potential of application RGC method in the real distributed system. Targeting the widely adopted multi-GPU system, we proposed an RGC system design call RedSync, which includes a set of optimizations to reduce communication bandwidth while introducing limited overhead. We examine the performance of RedSync on two different multiple GPU platforms, including a supercomputer and a multi-card server. Our test cases include image classification and language modeling tasks on Cifar10, ImageNet, Penn Treebank and Wiki2 datasets. For DNNs featured with high communication to computation ratio, which have long been considered with poor scalability, RedSync shows significant performance improvement.

##### Abstract (translated by Google)
数据并行已经成为将深度神经网络（DNN）训练扩展到多个计算节点的主要方法。考虑到局部模型的同步或迭代之间的梯度可能是大规模分布式训练的瓶颈，压缩通信流量最近引起了广泛的关注。在最近提出的几种压缩算法中，残差梯度压缩（RGC）是最成功的方法之一---它可以显着压缩消息大小（原始大小的0.1％）并仍然保持准确性。然而，关于压缩深度网络的文献几乎专注于寻找良好的压缩率，而RGC在实际实现中的效率则较少被研究。在本文中，我们探讨了应用RGC方法在实际分布式系统中的潜力。针对广泛采用的多GPU系统，我们提出了一个RGC系统设计调用RedSync，它包括一组优化，以减少通信带宽，同时引入有限的开销。我们在两个不同的多GPU平台上检查RedSync的性能，包括超级计算机和多卡服务器。我们的测试用例包括Cifar10，ImageNet，Penn Treebank和Wiki2数据集上的图像分类和语言建模任务。对于具有高通信与计算比率的DNN，长期以来一直被认为具有较差的可扩展性，RedSync显示出显着的性能提升。

##### URL
[http://arxiv.org/abs/1808.04357](http://arxiv.org/abs/1808.04357)

##### PDF
[http://arxiv.org/pdf/1808.04357](http://arxiv.org/pdf/1808.04357)

