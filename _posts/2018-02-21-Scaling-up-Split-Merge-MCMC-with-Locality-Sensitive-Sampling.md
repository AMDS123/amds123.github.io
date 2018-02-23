---
layout: post
title: "Scaling-up Split-Merge MCMC with Locality Sensitive Sampling"
date: 2018-02-21 07:03:32
categories: arXiv_AI
tags: arXiv_AI
author: Chen Luo, Anshumali Shrivastava
mathjax: true
---

* content
{:toc}

##### Abstract
Split-Merge MCMC (Monte Carlo Markov Chain) is one of the essential and popular variants of MCMC for problems when an MCMC state consists of an unknown number of components or clusters. It is well known that state-of-the-art methods for split-merge MCMC do not scale well. Strategies for rapid mixing requires smart and informative proposals to reduce the rejection rate. However, all known smart proposals involve cost at least linear in the size of the data $ \ge O(N)$, to suggest informative transitions. Thus, the cost of each iteration is prohibitive for massive scale datasets. It is further known that uninformative but computationally efficient proposals, such as random split-merge, leads to extremely slow convergence. This tradeoff between mixing time and per update cost seems hard to get around. In this paper, we get around this tradeoff by utilizing simple similarity information, such as cosine similarity, between the entity vectors to design a proposal distribution. Such information is readily available in almost all applications. We show that the recent use of locality sensitive hashing for efficient adaptive sampling can be leveraged to obtain a computationally efficient pseudo-marginal MCMC. The new split-merge MCMC has constant time update, just like random split-merge, and at the same time the proposal is informative and needs significantly fewer iterations than random split-merge. Overall, we obtain a sweet tradeoff between convergence and per update cost. As a direct consequence, our proposal, named LSHSM, is around 10x faster than the state-of-the-art sampling methods on both synthetic datasets and two large real datasets KDDCUP and PubMed with several millions of entities and thousands of cluster centers.

##### Abstract (translated by Google)
拆分合并MCMC（蒙特卡罗马尔可夫链）是MCMC状态由未知数量的组件或集群组成的问题MCMC的基本和流行变体之一。众所周知，拆分合并MCMC的最先进方法不能很好地扩展。快速混合策略需要智能和翔实的建议来降低拒收率。然而，所有已知的智能提案都涉及数据成本至少为线性的数据$ \ ge O（N）$，以提示信息转换。因此，每次迭代的成本对于大规模数据集都是不可行的。进一步已知的是，无信息但计算效率高的提议（例如随机拆分合并）导致收敛极其缓慢。混合时间和每次更新成本之间的这种折衷似乎很难解决。在本文中，我们利用实体向量之间的简单相似性信息（如余弦相似度）来设计投标分布，从而绕过这种折衷。几乎在所有应用中都可以获得这些信息。我们表明，最近使用局部敏感散列进行高效自适应采样可以用来获得计算效率高的伪边际MCMC。新的拆分合并MCMC具有恒定的时间更新，就像随机拆分合并一样，同时该提议具有信息量，并且需要比随机拆分合并少得多的迭代。总的来说，我们在收敛和每更新成本之间获得了一个甜蜜的折衷。作为直接后果，我们的名为LSHSM的提案比合成数据集和两个带有数百万实体和数千个聚类中心的大型真实数据集KDDCUP和PubMed的最先进的抽样方法速度快大约10倍。

##### URL
[http://arxiv.org/abs/1802.07444](http://arxiv.org/abs/1802.07444)

##### PDF
[http://arxiv.org/pdf/1802.07444](http://arxiv.org/pdf/1802.07444)

