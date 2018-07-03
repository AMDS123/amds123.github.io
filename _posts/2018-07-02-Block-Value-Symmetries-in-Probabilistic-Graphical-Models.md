---
layout: post
title: "Block-Value Symmetries in Probabilistic Graphical Models"
date: 2018-07-02 13:03:22
categories: arXiv_AI
tags: arXiv_AI Inference
author: Gagan Madan, Ankit Anand, Mausam, Parag Singla
mathjax: true
---

* content
{:toc}

##### Abstract
Several lifted inference algorithms for probabilistic graphical models first merge symmetric states into a single cluster (orbit) and then use these for downstream inference, via variations of orbital MCMC [Niepert, 2012]. These orbits are represented compactly using permutations over variables, and variable-value (VV) pairs, but these can miss several state symmetries in a domain. 
 We define the notion of permutations over block-value (BV) pairs, where a block is a set of variables. BV strictly generalizes VV symmetries, and can compute many more symmetries for increasing block sizes. To operationalize use of BV permutations in lifted inference, we describe 1) an algorithm to compute BV permutations given a block partition of the variables, 2) BV-MCMC, an extension of orbital MCMC that can sample from BV orbits, and 3) a heuristic to suggest good block partitions. Our experiments show that BV-MCMC can mix much faster compared to vanilla MCMC and orbital MCMC over VV permutations.

##### Abstract (translated by Google)
用于概率图形模型的几种提升推理算法首先将对称状态合并为单个聚类（轨道），然后通过轨道MCMC的变化将这些用于下游推理[Niepert，2012]。使用变量和变量值（VV）对的排列紧凑地表示这些轨道，但是这些轨道可能错过域中的几个状态对称性。
 我们定义了块值（BV）对上的置换概念，其中块是一组变量。 BV严格推广VV对称性，并且可以计算更多对称性以增加块大小。为了在提升推理中操作BV置换的使用，我们描述了1）在给定变量的块分区的情况下计算BV置换的算法，2）BV-MCMC，可以从BV轨道采样的轨道MCMC的扩展，以及3）a启发式建议好的块分区。我们的实验表明，与VV排列相比，BV-MCMC与香草MCMC和轨道MCMC的混合速度要快得多。

##### URL
[http://arxiv.org/abs/1807.00643](http://arxiv.org/abs/1807.00643)

##### PDF
[http://arxiv.org/pdf/1807.00643](http://arxiv.org/pdf/1807.00643)

