---
layout: post
title: "Efficient Linear Programming for Dense CRFs"
date: 2017-02-14 07:34:13
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Gradient_Descent
author: Thalaiyasingam Ajanthan, Alban Desmaison, Rudy Bunel, Mathieu Salzmann, Philip H.S. Torr, M. Pawan Kumar
mathjax: true
---

* content
{:toc}

##### Abstract
The fully connected conditional random field (CRF) with Gaussian pairwise potentials has proven popular and effective for multi-class semantic segmentation. While the energy of a dense CRF can be minimized accurately using a linear programming (LP) relaxation, the state-of-the-art algorithm is too slow to be useful in practice. To alleviate this deficiency, we introduce an efficient LP minimization algorithm for dense CRFs. To this end, we develop a proximal minimization framework, where the dual of each proximal problem is optimized via block coordinate descent. We show that each block of variables can be efficiently optimized. Specifically, for one block, the problem decomposes into significantly smaller subproblems, each of which is defined over a single pixel. For the other block, the problem is optimized via conditional gradient descent. This has two advantages: 1) the conditional gradient can be computed in a time linear in the number of pixels and labels; and 2) the optimal step size can be computed analytically. Our experiments on standard datasets provide compelling evidence that our approach outperforms all existing baselines including the previous LP based approach for dense CRFs.

##### Abstract (translated by Google)
具有高斯成对势的完全连通条件随机场（CRF）已经被证明在多类语义分割中是流行和有效的。尽管使用线性规划（LP）松弛可以精确地将密集的CRF的能量最小化，但是最先进的算法实际上太慢而不实用。为了缓解这个不足，我们引入了一个高效的密集CRF的LP最小化算法。为此，我们开发了一个近端最小化框架，每个近端问题的对偶通过块坐标下降进行优化。我们显示每个变量块可以被有效地优化。具体而言，对于一个块，该问题分解为显着较小的子问题，其中每个子问题都是在单个像素上定义的。对于另一个块，问题通过条件梯度下降进行优化。这具有两个优点：1）条件梯度可以在像素和标签的数量线性时间内计算;和2）可以分析计算最佳步长。我们对标准数据集的实验提供了令人信服的证据，表明我们的方法优于所有现有基线，包括以前基于LP的密集CRF方法。

##### URL
[https://arxiv.org/abs/1611.09718](https://arxiv.org/abs/1611.09718)

##### PDF
[https://arxiv.org/pdf/1611.09718](https://arxiv.org/pdf/1611.09718)

