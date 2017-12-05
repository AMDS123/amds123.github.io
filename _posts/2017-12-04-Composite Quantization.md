---
layout: post
title:  'Composite Quantization'
date:   2017-12-05 19:45:13
categories: arXiv_CV
tags: arXiv_CV
author: Jingdong Wang, Ting Zhang
---

* content
{:toc}

##### Abstract
This paper studies the compact coding approach to approximate nearest neighbor search. We introduce a composite quantization framework. It uses the composition of several ($M$) elements, each of which is selected from a different dictionary, to accurately approximate a $D$-dimensional vector, thus yielding accurate search, and represents the data vector by a short code composed of the indices of the selected elements in the corresponding dictionaries. Our key contribution lies in introducing a near-orthogonality constraint, which makes the search efficiency is guaranteed as the cost of the distance computation is reduced to $O(M)$ from $O(D)$ through a distance table lookup scheme. The resulting approach is called near-orthogonal composite quantization. We theoretically justify the equivalence between near-orthogonal composite quantization and minimizing an upper bound of a function formed by jointly considering the quantization error and the search cost according to a generalized triangle inequality. We empirically show the efficacy of the proposed approach over several benchmark datasets. In addition, we demonstrate the superior performances in other three applications: combination with inverted multi-index, quantizing the query for mobile search, and inner-product similarity search.

##### Abstract (translated by Google)
本文研究紧凑编码方法近似最近邻搜索。我们介绍一个复合量化框架。它使用几个（$ M $）元素的组合，每个元素是从不同的字典中选择的，以准确地近似一个$ D $维向量，从而产生精确的搜索，并且通过由相应字典中所选元素的索引。我们的主要贡献在于引入近正交性约束，这使得搜索效率得到保证，因为距离计算的成本通过距离表查找方案从$ O（D）$减少到$ O（M）$。所得到的方法被称为近正交复合量化。我们从理论上证明近似正交复合量化的等价性，并根据广义三角不等式使联合考虑量化误差和搜索代价形成的函数的上界最小化。我们经验性地显示了提出的方法在几个基准数据集上的功效。此外，我们在其他三种应用中展示了出众的性能：与倒排多指数相结合，量化移动搜索查询和内积相似搜索。

##### URL
[http://arxiv.org/abs/1712.00955](http://arxiv.org/abs/1712.00955)

