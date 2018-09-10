---
layout: post
title: "Tensor Ring Decomposition with Rank Minimization on Latent Space: An Efficient Approach for Tensor Completion"
date: 2018-09-07 03:05:08
categories: arXiv_CV
tags: arXiv_CV Regularization Optimization
author: Longhao Yuan, Chao Li, Danilo Mandic, Jianting Cao, Qibin Zhao
mathjax: true
---

* content
{:toc}

##### Abstract
In tensor completion tasks, the traditional low-rank tensor decomposition models suffer from laborious model selection problem due to high model sensitivity. Especially for tensor ring (TR) decomposition, the number of model possibility grows exponentially with the tensor order, which makes it rather challenging to find the optimal TR decomposition. In this paper, by exploiting the low-rank structure on TR latent space, we propose a novel tensor completion method, which is robust to model selection. In contrast to imposing low-rank constraint on the data space, we introduce nuclear norm regularization on the latent TR factors, resulting in that the optimization step using singular value decomposition (SVD) can be performed at a much smaller scale. By leveraging the alternating direction method of multipliers (ADMM) scheme, the latent TR factors with optimal rank and the recovered tensor can be obtained simultaneously. Our proposed algorithm effectively alleviates the burden of TR-rank selection, therefore the computational cost is greatly reduced. The extensive experimental results on synthetic data and real-world data demonstrate the superior high performance and efficiency of the proposed approach against the state-of-the-art algorithms.

##### Abstract (translated by Google)
在张量完成任务中，由于模型灵敏度高，传统的低秩张量分解模型存在费力的模型选择问题。特别是对于张量环（TR）分解，模型可能性的数量随着张量阶数呈指数增长，这使得找到最优TR分解具有相当大的挑战性。本文利用TR潜空间的低秩结构，提出了一种新的张量完备方法，该方法对模型选择具有鲁棒性。与对数据空间施加低秩约束相反，我们在潜在TR因子上引入核范数正则化，导致使用奇异值分解（SVD）的优化步骤可以以小得多的规模执行。通过利用交替方向乘法器（ADMM）方案，可以同时获得具有最优秩和恢复张量的潜在TR因子。我们提出的算法有效地减轻了TR秩选择的负担，因此大大降低了计算成本。对合成数据和实际数据的广泛实验结果表明，该方法针对最先进的算法具有卓越的高性能和高效率。

##### URL
[http://arxiv.org/abs/1809.02288](http://arxiv.org/abs/1809.02288)

##### PDF
[http://arxiv.org/pdf/1809.02288](http://arxiv.org/pdf/1809.02288)

