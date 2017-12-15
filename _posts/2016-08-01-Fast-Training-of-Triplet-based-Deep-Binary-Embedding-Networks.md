---
layout: post
title: "Fast Training of Triplet-based Deep Binary Embedding Networks"
date: 2016-08-01 01:52:57
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Embedding CNN Optimization Inference Classification
author: Bohan Zhuang, Guosheng Lin, Chunhua Shen, Ian Reid
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we aim to learn a mapping (or embedding) from images to a compact binary space in which Hamming distances correspond to a ranking measure for the image retrieval task. We make use of a triplet loss because this has been shown to be most effective for ranking problems. However, training in previous works can be prohibitively expensive due to the fact that optimization is directly performed on the triplet space, where the number of possible triplets for training is cubic in the number of training examples. To address this issue, we propose to formulate high-order binary codes learning as a multi-label classification problem by explicitly separating learning into two interleaved stages. To solve the first stage, we design a large-scale high-order binary codes inference algorithm to reduce the high-order objective to a standard binary quadratic problem such that graph cuts can be used to efficiently infer the binary code which serve as the label of each training datum. In the second stage we propose to map the original image to compact binary codes via carefully designed deep convolutional neural networks (CNNs) and the hashing function fitting can be solved by training binary CNN classifiers. An incremental/interleaved optimization strategy is proffered to ensure that these two steps are interactive with each other during training for better accuracy. We conduct experiments on several benchmark datasets, which demonstrate both improved training time (by as much as two orders of magnitude) as well as producing state-of-the-art hashing for various retrieval tasks.

##### Abstract (translated by Google)
在本文中，我们的目标是学习从图像映射（或嵌入）到紧凑的二进制空间，其中汉明距离对应于图像检索任务的排序测量。我们利用三重损失，因为这已经被证明是排序问题最有效的。然而，由于在三元组空间上直接进行优化的事实，以前的工作中的训练可能过于昂贵，训练例子中训练的可能三元组的数目是立方。为了解决这个问题，我们提出将高阶二进制编码学习作为一个多标签分类问题，将学习明确地分为两个交错阶段。为了解决第一阶段的问题，我们设计了一个大规模的高阶二进制编码推理算法，将高阶目标降为一个标准二进制二次问题，从而可以使用图形切割有效地推导出作为标签的二进制编码每个训练数据。在第二阶段，我们提出通过精心设计的深度卷积神经网络（CNNs）将原始图像映射为紧凑二进制编码，并通过训练二进制CNN分类器来解决哈希函数拟合问题。提供递增/交错优化策略以确保在训练期间这两个步骤彼此交互以获得更好的准确性。我们在几个基准数据集上进行了实验，这些数据集证明了改进的训练时间（多达两个数量级）以及为各种检索任务生成最新的散列。

##### URL
[https://arxiv.org/abs/1603.02844](https://arxiv.org/abs/1603.02844)

##### PDF
[https://arxiv.org/pdf/1603.02844](https://arxiv.org/pdf/1603.02844)

