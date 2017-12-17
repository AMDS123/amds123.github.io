---
layout: post
title: "Aggregated Wasserstein Metric and State Registration for Hidden Markov Models"
date: 2017-11-19 20:19:50
categories: arXiv_CV
tags: arXiv_CV Optimization Classification Relation
author: Yukun Chen, Jianbo Ye, Jia Li
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a framework, named Aggregated Wasserstein, for computing a dissimilarity measure or distance between two Hidden Markov Models with state conditional distributions being Gaussian. For such HMMs, the marginal distribution at any time position follows a Gaussian mixture distribution, a fact exploited to softly match, aka register, the states in two HMMs. We refer to such HMMs as Gaussian mixture model-HMM (GMM-HMM). The registration of states is inspired by the intrinsic relationship of optimal transport and the Wasserstein metric between distributions. Specifically, the components of the marginal GMMs are matched by solving an optimal transport problem where the cost between components is the Wasserstein metric for Gaussian distributions. The solution of the optimization problem is a fast approximation to the Wasserstein metric between two GMMs. The new Aggregated Wasserstein distance is a semi-metric and can be computed without generating Monte Carlo samples. It is invariant to relabeling or permutation of states. The distance is defined meaningfully even for two HMMs that are estimated from data of different dimensionality, a situation that can arise due to missing variables. This distance quantifies the dissimilarity of GMM-HMMs by measuring both the difference between the two marginal GMMs and that between the two transition matrices. Our new distance is tested on tasks of retrieval, classification, and t-SNE visualization of time series. Experiments on both synthetic and real data have demonstrated its advantages in terms of accuracy as well as efficiency in comparison with existing distances based on the Kullback-Leibler divergence.

##### Abstract (translated by Google)
我们提出了一个名为Aggregated Wasserstein的框架，用于计算状态条件分布为高斯的两个隐马尔可夫模型之间的相异度量或距离。对于这样的隐马尔可夫模型，在任何时间位置的边缘分布遵循高斯混合分布，这个事实被利用来软匹配，即寄存器，两个隐马尔可夫模型中的状态。我们将这种HMM称为高斯混合模型-HMM（GMM-HMM）。国家的注册受到最优运输和分布之间的瓦塞斯坦度量的内在关系的启发。具体而言，通过求解最优运输问题来匹配边际GMM的成分，其中成分之间的成本是用于高斯分布的Wasserstein度量。优化问题的解决方案是两个GMM之间的Wasserstein度量的快速近似。新的聚合Wasserstein距离是一个半度量，可以计算而不产生蒙特卡罗样本。对国家进行重新标记或置换是不变的。即使对于从不同维度的数据估计的两个HMM，也可以有意义地定义距离，这是由于缺少变量而可能出现的情况。该距离通过测量两个边际GMM之间的差异和两个过渡矩阵之间的差异来量化GMM-HMM的不相似度。我们的新距离在时间序列的检索，分类和t-SNE可视化任务上进行测试。对于合成数据和真实数据的实验已经证明了其与基于Kullback-Leibler散度的现有距离相比在准确性和效率方面的优势。

##### URL
[https://arxiv.org/abs/1711.05792](https://arxiv.org/abs/1711.05792)

##### PDF
[https://arxiv.org/pdf/1711.05792](https://arxiv.org/pdf/1711.05792)

