---
layout: post
title: "Efficient Progressive Neural Architecture Search"
date: 2018-08-01 15:56:08
categories: arXiv_CV
tags: arXiv_CV Image_Classification Optimization Classification Prediction
author: Juan-Manuel Perez-Rua, Moez Baccouche, Stephane Pateux
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the difficult problem of finding an optimal neural architecture design for a given image classification task. We propose a method that aggregates two main results of the previous state-of-the-art in neural architecture search. These are, appealing to the strong sampling efficiency of a search scheme based on sequential model-based optimization (SMBO), and increasing training efficiency by sharing weights among sampled architectures. Sequential search has previously demonstrated its capabilities to find state-of-the-art neural architectures for image classification. However, its computational cost remains high, even unreachable under modest computational settings. Affording SMBO with weight-sharing alleviates this problem. On the other hand, progressive search with SMBO is inherently greedy, as it leverages a learned surrogate function to predict the validation error of neural architectures. This prediction is directly used to rank the sampled neural architectures. We propose to attenuate the greediness of the original SMBO method by relaxing the role of the surrogate function so it predicts architecture sampling probability instead. We demonstrate with experiments on the CIFAR-10 dataset that our method, denominated Efficient progressive neural architecture search (EPNAS), leads to increased search efficiency, while retaining competitiveness of found architectures.

##### Abstract (translated by Google)
本文讨论了为给定的图像分类任务找到最优神经结构设计的难题。我们提出了一种方法，该方法汇总了神经架构搜索中先前技术水平的两个主要结果。这些都吸引了基于基于序列模型的优化（SMBO）的搜索方案的强采样效率，并通过在采样架构之间共享权重来提高训练效率。顺序搜索之前已经证明了其为图像分类找到最先进的神经架构的能力。然而，它的计算成本仍然很高，即使在适度的计算设置下也无法达到。通过分担重量来提供SMBO可以缓解这个问题。另一方面，使用SMBO的渐进式搜索本质上是贪婪的，因为它利用学习的替代函数来预测神经架构的验证错误。该预测直接用于对采样的神经架构进行排名。我们建议通过放宽代理函数的作用来减弱原始SMBO方法的贪婪，从而预测架构抽样概率。我们通过对CIFAR-10数据集的实验证明，我们的方法，称为高效渐进式神经结构搜索（EPNAS），可以提高搜索效率，同时保持已发现架构的竞争力。

##### URL
[https://arxiv.org/abs/1808.00391](https://arxiv.org/abs/1808.00391)

##### PDF
[https://arxiv.org/pdf/1808.00391](https://arxiv.org/pdf/1808.00391)

