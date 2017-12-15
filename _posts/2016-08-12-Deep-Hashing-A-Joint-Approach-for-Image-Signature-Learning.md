---
layout: post
title: "Deep Hashing: A Joint Approach for Image Signature Learning"
date: 2016-08-12 02:00:08
categories: arXiv_CV
tags: arXiv_CV Image_Classification Optimization Classification Deep_Learning Quantitative
author: Yadong Mu, Zhu Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Similarity-based image hashing represents crucial technique for visual data storage reduction and expedited image search. Conventional hashing schemes typically feed hand-crafted features into hash functions, which separates the procedures of feature extraction and hash function learning. In this paper, we propose a novel algorithm that concurrently performs feature engineering and non-linear supervised hashing function learning. Our technical contributions in this paper are two-folds: 1) deep network optimization is often achieved by gradient propagation, which critically requires a smooth objective function. The discrete nature of hash codes makes them not amenable for gradient-based optimization. To address this issue, we propose an exponentiated hashing loss function and its bilinear smooth approximation. Effective gradient calculation and propagation are thereby enabled; 2) pre-training is an important trick in supervised deep learning. The impact of pre-training on the hash code quality has never been discussed in current deep hashing literature. We propose a pre-training scheme inspired by recent advance in deep network based image classification, and experimentally demonstrate its effectiveness. Comprehensive quantitative evaluations are conducted on several widely-used image benchmarks. On all benchmarks, our proposed deep hashing algorithm outperforms all state-of-the-art competitors by significant margins. In particular, our algorithm achieves a near-perfect 0.99 in terms of Hamming ranking accuracy with only 12 bits on MNIST, and a new record of 0.74 on the CIFAR10 dataset. In comparison, the best accuracies obtained on CIFAR10 by existing hashing algorithms without or with deep networks are known to be 0.36 and 0.58 respectively.

##### Abstract (translated by Google)
基于相似性的图像哈希表示减少视觉数据存储和加速图像搜索的关键技术。传统的散列方案通常将手工特征提供给散列函数，散列函数分离了特征提取和散列函数学习的过程。在本文中，我们提出了一种同时执行特征工程和非线性监督哈希函数学习的新算法。我们在本文中的技术贡献有两个方面：1）深度网络优化通常通过梯度传播来实现，这关键地需要一个平滑的目标函数。散列码的离散性使得它们不适合基于梯度的优化。为了解决这个问题，我们提出了一个指数哈希损失函数及其双线性平滑近似。由此启用有效的梯度计算和传播; 2）预训练是监督式深度学习的重要手段。预训练对散列码质量的影响在目前的深度散列文献中从未讨论过。我们提出了一个基于深度网络的图像分类的最新进展，并通过实验证明其有效性的预训练方案。对几个广泛使用的图像基准进行全面的定量评估。在所有的基准测试中，我们提出的深度哈希算法的表现都优于所有最先进的竞争对手。特别地，我们的算法在MNIST上只有12比特的汉明（Hamming）排序精度方面达到近乎完美的0.99，而CIFAR10数据集上的新记录为0.74。相比之下，现有的散列算法在CIFAR10上获得的最高精度分别为0.36和0.58。

##### URL
[https://arxiv.org/abs/1608.03658](https://arxiv.org/abs/1608.03658)

##### PDF
[https://arxiv.org/pdf/1608.03658](https://arxiv.org/pdf/1608.03658)

