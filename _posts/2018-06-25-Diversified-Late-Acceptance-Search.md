---
layout: post
title: "Diversified Late Acceptance Search"
date: 2018-06-25 08:47:08
categories: arXiv_AI
tags: arXiv_AI
author: Majid Namazi, Conrad Sanderson, M.A. Hakim Newton, M.M.A. Polash, Abdul Sattar
mathjax: true
---

* content
{:toc}

##### Abstract
The well-known Late Acceptance Hill Climbing (LAHC) search aims to overcome the main downside of traditional Hill Climbing (HC) search, which is often quickly trapped in a local optimum due to strictly accepting only non-worsening moves within each iteration. In contrast, LAHC also accepts worsening moves, by keeping a circular array of fitness values of previously visited solutions and comparing the fitness values of candidate solutions against the least recent element in the array. While the straightforward strategy followed by LAHC has proven effective, there are nevertheless situations where LAHC can unfortunately behave in a similar manner to HC, even when using a large fitness array. For example, when the same fitness value is stored many times in the array, particularly when a new local optimum is found. To address this shortcoming, we propose to improve both the diversity of the accepted solutions and the diversity of values in the array through new acceptance and replacement strategies. The proposed Diversified Late Acceptance Search approach is shown to outperform the current state-of-the-art LAHC method on benchmark sets of Travelling Salesman Problem and Quadratic Assignment Problem instances.

##### Abstract (translated by Google)
着名的Late Acceptance Hill Climbing（LAHC）搜索旨在克服传统爬山（HC）搜索的主要缺点，由于在每次迭代中严格接受非恶化的移动，该搜索通常会很快陷入局部最优。相比之下，LAHC也接受恶化的举动，保留先前访问的解决方案的循环阵列的适应值，并将候选解的适应值与阵列中最近的元素进行比较。尽管LAHC所遵循的直接策略已被证明是有效的，但即使在使用大型健身阵列时，LAHC仍然可能表现出与HC类似的情况。例如，当相同的适应值在阵列中多次存储时，特别是当找到新的局部最优值时。为了解决这个缺点，我们建议通过新的接受和替代策略来改善接受解决方案的多样性和阵列中价值的多样性。所提出的Diversified Late Acceptance Search方法被证明在基于旅行商问题和二次分配问题实例的基准集上胜过当前最先进的LAHC方法。

##### URL
[http://arxiv.org/abs/1806.09328](http://arxiv.org/abs/1806.09328)

##### PDF
[http://arxiv.org/pdf/1806.09328](http://arxiv.org/pdf/1806.09328)

