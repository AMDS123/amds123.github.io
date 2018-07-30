---
layout: post
title: "Entropic Latent Variable Discovery"
date: 2018-07-26 23:30:09
categories: arXiv_AI
tags: arXiv_AI Relation
author: Murat Kocaoglu, Sanjay Shakkottai, Alexandros G. Dimakis, Constantine Caramanis, Sriram Vishwanath
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the problem of discovering the simplest latent variable that can make two observed discrete variables conditionally independent. This problem has appeared in the literature as probabilistic latent semantic analysis (pLSA), and has connections to non-negative matrix factorization. When the simplicity of the variable is measured through its cardinality, we show that a solution to this latent variable discovery problem can be used to distinguish direct causal relations from spurious correlations among almost all joint distributions on simple causal graphs with two observed variables. Conjecturing a similar identifiability result holds with Shannon entropy, we study a loss function that trades-off between entropy of the latent variable and the conditional mutual information of the observed variables. We then propose a latent variable discovery algorithm -- LatentSearch -- and show that its stationary points are the stationary points of our loss function. We experimentally show that LatentSearch can indeed be used to distinguish direct causal relations from spurious correlations.

##### Abstract (translated by Google)
我们考虑发现最简单的潜在变量的问题，该变量可以使两个观察到的离散变量有条件地独立。这个问题在文献中作为概率潜在语义分析（pLSA）出现，并且与非负矩阵分解有关。当通过其基数来测量变量的简单性时，我们证明了这个潜在变量发现问题的解决方案可用于区分直接因果关系与几乎所有联合分布之间的虚假相关性，简单因果图上有两个观察变量。使用香农熵推测类似的可识别结果，我们研究了潜在变量的熵与观察到的变量的条件互信息之间的折衷函数。然后，我们提出潜在变量发现算法 -  LatentSearch  - 并显示其静止点是我们的损失函数的静止点。我们通过实验证明，LatentSearch确实可以用于区分直接因果关系和虚假关联。

##### URL
[http://arxiv.org/abs/1807.10399](http://arxiv.org/abs/1807.10399)

##### PDF
[http://arxiv.org/pdf/1807.10399](http://arxiv.org/pdf/1807.10399)

