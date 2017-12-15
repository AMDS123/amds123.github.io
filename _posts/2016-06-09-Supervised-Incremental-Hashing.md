---
layout: post
title: "Supervised Incremental Hashing"
date: 2016-06-09 17:24:25
categories: arXiv_CV
tags: arXiv_CV Classification
author: Bahadir Ozdemir, Mahyar Najibi, Larry S. Davis
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an incremental strategy for learning hash functions with kernels for large-scale image search. Our method is based on a two-stage classification framework that treats binary codes as intermediate variables between the feature space and the semantic space. In the first stage of classification, binary codes are considered as class labels by a set of binary SVMs; each corresponds to one bit. In the second stage, binary codes become the input space of a multi-class SVM. Hash functions are learned by an efficient algorithm where the NP-hard problem of finding optimal binary codes is solved via cyclic coordinate descent and SVMs are trained in a parallelized incremental manner. For modifications like adding images from a previously unseen class, we describe an incremental procedure for effective and efficient updates to the previous hash functions. Experiments on three large-scale image datasets demonstrate the effectiveness of the proposed hashing method, Supervised Incremental Hashing (SIH), over the state-of-the-art supervised hashing methods.

##### Abstract (translated by Google)
我们提出了一个增量学习散列函数的核函数，用于大规模图像搜索。我们的方法是基于一个两阶段的分类框架，把二进制代码作为特征空间和语义空间之间的中间变量。在分类的第一阶段，二进制代码被一组二进制SVM视为类标签;每个对应一个位。在第二阶段，二进制代码成为多类SVM的输入空间。哈希函数是通过一种有效的算法学习的，其中通过循环坐标下降求解最优二进制码的NP难问题并且以并行增量方式训练SVM。对于像从前面看不见的类中添加图像那样的修改，我们描述了一个增量过程，以便对之前的哈希函数进行有效且高效的更新。在三个大规模图像数据集上的实验证明了所提出的哈希方法监督式增量散列（SIH）相对于最先进的监督式哈希方法的有效性。

##### URL
[https://arxiv.org/abs/1604.07342](https://arxiv.org/abs/1604.07342)

##### PDF
[https://arxiv.org/pdf/1604.07342](https://arxiv.org/pdf/1604.07342)

