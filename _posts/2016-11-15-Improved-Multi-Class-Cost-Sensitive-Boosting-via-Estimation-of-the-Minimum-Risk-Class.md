---
layout: post
title: "Improved Multi-Class Cost-Sensitive Boosting via Estimation of the Minimum-Risk Class"
date: 2016-11-15 19:29:30
categories: arXiv_CV
tags: arXiv_CV Classification
author: Ron Appel, Xavier Burgos-Artizzu, Pietro Perona
mathjax: true
---

* content
{:toc}

##### Abstract
We present a simple unified framework for multi-class cost-sensitive boosting. The minimum-risk class is estimated directly, rather than via an approximation of the posterior distribution. Our method jointly optimizes binary weak learners and their corresponding output vectors, requiring classes to share features at each iteration. By training in a cost-sensitive manner, weak learners are invested in separating classes whose discrimination is important, at the expense of less relevant classification boundaries. Additional contributions are a family of loss functions along with proof that our algorithm is Boostable in the theoretical sense, as well as an efficient procedure for growing decision trees for use as weak learners. We evaluate our method on a variety of datasets: a collection of synthetic planar data, common UCI datasets, MNIST digits, SUN scenes, and CUB-200 birds. Results show state-of-the-art performance across all datasets against several strong baselines, including non-boosting multi-class approaches.

##### Abstract (translated by Google)
我们提出了一个简单的多级成本敏感推进的统一框架。最低风险等级是直接估计的，而不是通过近似后验分布。我们的方法联合优化二元弱学习者及其相应的输出向量，要求类在每次迭代中共享特征。通过以成本敏感的方式进行培训，弱学习者被投入分离重要的歧视类别，代价是不太相关的分类界限。额外的贡献是一系列的损失函数，以及证明我们的算法在理论意义上是Boostable的，以及一个用于增长决策树以作为弱学习者使用的有效过程。我们在各种数据集上评估我们的方法：合成平面数据，常用UCI数据集，MNIST数字，SUN场景和CUB-200鸟类的集合。结果显示，在所有数据集中，与几个强大的基线相比，其性能表现最先进，包括非增强型多类方法。

##### URL
[https://arxiv.org/abs/1607.03547](https://arxiv.org/abs/1607.03547)

##### PDF
[https://arxiv.org/pdf/1607.03547](https://arxiv.org/pdf/1607.03547)

