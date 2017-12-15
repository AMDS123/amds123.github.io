---
layout: post
title: "An Efficient Multilinear Optimization Framework for Hypergraph Matching"
date: 2016-05-24 19:06:19
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Quynh Nguyen, Francesco Tudisco, Antoine Gautier, Matthias Hein
mathjax: true
---

* content
{:toc}

##### Abstract
Hypergraph matching has recently become a popular approach for solving correspondence problems in computer vision as it allows to integrate higher-order geometric information. Hypergraph matching can be formulated as a third-order optimization problem subject to the assignment constraints which turns out to be NP-hard. In recent work, we have proposed an algorithm for hypergraph matching which first lifts the third-order problem to a fourth-order problem and then solves the fourth-order problem via optimization of the corresponding multilinear form. This leads to a tensor block coordinate ascent scheme which has the guarantee of providing monotonic ascent in the original matching score function and leads to state-of-the-art performance both in terms of achieved matching score and accuracy. In this paper we show that the lifting step to a fourth-order problem can be avoided yielding a third-order scheme with the same guarantees and performance but being two times faster. Moreover, we introduce a homotopy type method which further improves the performance.

##### Abstract (translated by Google)
超图匹配最近成为解决计算机视觉中的对应问题的流行方法，因为它允许整合更高阶的几何信息。超图的匹配可以表示为一个三阶优化问题，受分配约束条件的约束为NP难。在最近的工作中，我们提出了一种超图匹配算法，首先将三阶问题提升为四阶问题，然后通过对应多线性形式的优化求解四阶问题。这导致张量块坐标上升方案，其在原始匹配分数函数中提供单调上升的保证，并导致在达到的匹配分数和准确度方面的最新性能。在本文中，我们表明，提升到四阶问题的步骤可以避免产生具有相同保证和性能但速度提高两倍的三阶方案。而且，我们引入了同伦类型的方法，进一步提高了性能。

##### URL
[https://arxiv.org/abs/1511.02667](https://arxiv.org/abs/1511.02667)

##### PDF
[https://arxiv.org/pdf/1511.02667](https://arxiv.org/pdf/1511.02667)

