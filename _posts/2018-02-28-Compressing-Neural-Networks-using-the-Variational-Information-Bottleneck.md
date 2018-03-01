---
layout: post
title: "Compressing Neural Networks using the Variational Information Bottleneck"
date: 2018-02-28 13:26:46
categories: arXiv_CV
tags: arXiv_CV Regularization Sparse
author: Bin Dai, Chen Zhu, David Wipf
mathjax: true
---

* content
{:toc}

##### Abstract
Neural networks can be compressed to reduce memory and computational requirements, or to increase accuracy by facilitating the use of a larger base architecture. In this paper we focus on pruning individual neurons, which can simultaneously trim model size, FLOPs, and run-time memory. To improve upon the performance of existing compression algorithms we utilize the information bottleneck principle instantiated via a tractable variational bound. Minimization of this information theoretic bound reduces the redundancy between adjacent layers by aggregating useful information into a subset of neurons that can be preserved. In contrast, the activations of disposable neurons are shut off via an attractive form of sparse regularization that emerges naturally from this framework, providing tangible advantages over traditional sparsity penalties without contributing additional tuning parameters to the energy landscape. We demonstrate state-of-the-art compression rates across an array of datasets and network architectures.

##### Abstract (translated by Google)
可以对神经网络进行压缩以减少内存和计算要求，或者通过促进使用更大的基础体系结构来提高准确性。在本文中，我们重点讨论修剪单个神经元，它们可以同时修正模型大小，FLOP和运行时内存。为了改进现有压缩算法的性能，我们利用通过易处理的变分边界实例化的信息瓶颈原理。通过将有用的信息聚合到可以保存的神经元的子集中，最小化该信息理论界限减少了相邻层之间的冗余。相比之下，一次性神经元的激活是通过一种吸引形式的稀疏正则化来关闭的，稀疏正则化从该框架中自然产生，与传统的稀疏性惩罚相比，提供了实实在在的优势，而无需为能源格局贡献额外的调整参数。我们在数据集和网络架构阵列中展示了最先进的压缩率。

##### URL
[http://arxiv.org/abs/1802.10399](http://arxiv.org/abs/1802.10399)

##### PDF
[http://arxiv.org/pdf/1802.10399](http://arxiv.org/pdf/1802.10399)

