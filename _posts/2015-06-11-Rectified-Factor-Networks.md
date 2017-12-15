---
layout: post
title: "Rectified Factor Networks"
date: 2015-06-11 21:27:53
categories: arXiv_CV
tags: arXiv_CV Regularization Sparse
author: Djork-Arné Clevert, Andreas Mayr, Thomas Unterthiner, Sepp Hochreiter
mathjax: true
---

* content
{:toc}

##### Abstract
We propose rectified factor networks (RFNs) to efficiently construct very sparse, non-linear, high-dimensional representations of the input. RFN models identify rare and small events in the input, have a low interference between code units, have a small reconstruction error, and explain the data covariance structure. RFN learning is a generalized alternating minimization algorithm derived from the posterior regularization method which enforces non-negative and normalized posterior means. We proof convergence and correctness of the RFN learning algorithm. On benchmarks, RFNs are compared to other unsupervised methods like autoencoders, RBMs, factor analysis, ICA, and PCA. In contrast to previous sparse coding methods, RFNs yield sparser codes, capture the data's covariance structure more precisely, and have a significantly smaller reconstruction error. We test RFNs as pretraining technique for deep networks on different vision datasets, where RFNs were superior to RBMs and autoencoders. On gene expression data from two pharmaceutical drug discovery studies, RFNs detected small and rare gene modules that revealed highly relevant new biological insights which were so far missed by other unsupervised methods.

##### Abstract (translated by Google)
我们提出纠正因子网络（RFN），以有效地构建输入的非常稀疏，非线性，高维表示。 RFN模型识别输入中的罕见和小事件，代码单元之间具有低干扰，具有小的重构误差，并解释数据协方差结构。 RFN学习是一种广义交替最小化算法，由后验正则化方法导出，强制非负和归一化后验均值。我们证明了RFN学习算法的收敛性和正确性。在基准测试中，将RFN与其他无监督方法（如自动编码器，RBM，因子分析，ICA和PCA）进行比较。与以前的稀疏编码方法相比，RFN产生更稀疏的代码，更精确地捕获数据的协方差结构，并具有显着更小的重构误差。我们将RFN作为不同视觉数据集上深度网络的预训练技术进行测试，其中RFN优于RBM和自编码器。在两项药物开发研究的基因表达数据中，RFN检测到小而稀有的基因模块，揭示了高度相关的新的生物学见解，迄今为止，其他无监督的方法都忽略了这些新的生物学见解。

##### URL
[https://arxiv.org/abs/1502.06464](https://arxiv.org/abs/1502.06464)

##### PDF
[https://arxiv.org/pdf/1502.06464](https://arxiv.org/pdf/1502.06464)

