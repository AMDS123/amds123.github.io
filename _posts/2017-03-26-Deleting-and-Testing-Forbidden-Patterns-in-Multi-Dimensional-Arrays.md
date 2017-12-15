---
layout: post
title: "Deleting and Testing Forbidden Patterns in Multi-Dimensional Arrays"
date: 2017-03-26 12:43:59
categories: arXiv_CV
tags: arXiv_CV
author: Omri Ben-Eliezer, Simon Korman, Daniel Reichman
mathjax: true
---

* content
{:toc}

##### Abstract
Understanding the local behaviour of structured multi-dimensional data is a fundamental problem in various areas of computer science. As the amount of data is often huge, it is desirable to obtain sublinear time algorithms, and specifically property testers, to understand local properties of the data. We focus on the natural local problem of testing pattern freeness: given a large $d$-dimensional array $A$ and a fixed $d$-dimensional pattern $P$ over a finite alphabet, we say that $A$ is $P$-free if it does not contain a copy of the forbidden pattern $P$ as a consecutive subarray. The distance of $A$ to $P$-freeness is the fraction of entries of $A$ that need to be modified to make it $P$-free. For any $\epsilon \in [0,1]$ and any large enough pattern $P$ over any alphabet, other than a very small set of exceptional patterns, we design a tolerant tester that distinguishes between the case that the distance is at least $\epsilon$ and the case that it is at most $a_d \epsilon$, with query complexity and running time $c_d \epsilon^{-1}$, where $a_d < 1$ and $c_d$ depend only on $d$. To analyze the testers we establish several combinatorial results, including the following $d$-dimensional modification lemma, which might be of independent interest: for any large enough pattern $P$ over any alphabet (excluding a small set of exceptional patterns for the binary case), and any array $A$ containing a copy of $P$, one can delete this copy by modifying one of its locations without creating new $P$-copies in $A$. Our results address an open question of Fischer and Newman, who asked whether there exist efficient testers for properties related to tight substructures in multi-dimensional structured data. They serve as a first step towards a general understanding of local properties of multi-dimensional arrays, as any such property can be characterized by a fixed family of forbidden patterns.

##### Abstract (translated by Google)
了解结构化多维数据的局部行为是计算机科学各个领域的一个基本问题。由于数据量通常很大，因此需要获得次线性时间算法，特别是属性测试者，以了解数据的局部属性。我们关注测试模式自由度的自然局部问题：给定一个大的$ d $维数组$ A $和一个固定的$ d $维数模式$ P $超过一个有限字母表，我们说$ A $是$ P $ -free，如果它不包含作为连续子数组的禁止模式$ P $的副本。 $ A $到$ P $ -freeness的距离是$ A $条目的一小部分，需要修改它以使$ P $ -free。对于任何$ \ epsilon \ in [0,1] $和足够大的模式$ P $而不是任何字母表，除了一小部分特殊模式外，我们设计了一个宽容的测试器来区分距离是最少$ \ epsilon $，最多$ a_d \ epsilon $，查询复杂度和运行时间$ c_d \ epsilon ^ { -  1} $，其中$ a_d <1 $和$ c_d $仅依赖于$ d $。为了分析测试人员，我们建立了几个组合的结果，其中包括下面的$ d $维修改引理，它可能是独立的兴趣：任何足够大的模式$ P $超过任何字母表（不包括二进制的一小组例外模式case）和任何包含$ P $副本的数组$ A $，可以通过修改其中一个位置来删除此副本，而不必在$ A $中创建新的$ P $ -copies。我们的研究结果解决了Fischer和Newman的一个悬而未决的问题，他问在多维结构化数据中是否存在与紧密子结构相关的性质的有效测试器。它们是对多维阵列的局部性质的一般理解的第一步，因为任何这样的性质可以由固定的禁止模式族来表征。

##### URL
[https://arxiv.org/abs/1607.03961](https://arxiv.org/abs/1607.03961)

##### PDF
[https://arxiv.org/pdf/1607.03961](https://arxiv.org/pdf/1607.03961)

