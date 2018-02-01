---
layout: post
title: "A Revisit of Hashing Algorithms for Approximate Nearest Neighbor Search"
date: 2018-01-31 04:21:33
categories: arXiv_CV
tags: arXiv_CV
author: Deng Cai
mathjax: true
---

* content
{:toc}

##### Abstract
Approximate Nearest Neighbor Search (ANNS) is a fundamental problem in many areas of machine learning and data mining. During the past decade, numerous hashing algorithms are proposed to solve this problem. Every proposed algorithm claims outperform other state-of-the-art hashing algorithms. However, the evaluation of these hashing papers was not thorough enough, and those claims should be re-examined. The ultimate goal of an ANNS method is returning the most accurate answers (nearest neighbors) in the shortest time. If implemented correctly, almost all the hashing methods will have their performance improved as the code length increases. However, many existing hashing papers only report the performance with the code length shorter than 128. In this paper, we carefully revisit the problem of search with the hash index and make a thorough comparison of many popular hashing algorithms. Surprisingly, the random-projection-based Locality Sensitive Hashing (LSH) ranked the second among twelve compared popular hashing algorithms, while all the other eleven hashing papers claim to outperform LSH. Despite the extreme simplicity of random-projection-based LSH, our results show that the capability of this algorithm has been far underestimated. For the sake of reproducibility, all the codes used in the paper are released on GitHub, which can be used as a testing platform for a fair comparison between various hashing algorithms.

##### Abstract (translated by Google)
近似最近邻搜索（ANNS）是机器学习和数据挖掘的许多领域的一个基本问题。在过去的十年中，提出了许多哈希算法来解决这个问题。每个提出的算法都要比其他最先进的散列算法优越。然而，这些哈希文件的评估不够彻底，这些索赔应该重新审查。 ANNS方法的最终目标是在最短的时间内返回最准确的答案（最近的邻居）。如果实现正确，随着代码长度的增加，几乎所有的哈希方法都会提高性能。然而，现有的许多哈希表只报告码长小于128的性能。本文中，我们仔细回顾了哈希索引的搜索问题，并对许多流行的哈希算法进行了详细的比较。令人惊讶的是，基于随机投影的局部敏感散列（LSH）在十二个比较流行的散列算法中排名第二，而另外十一个散列文件声称胜过LSH。尽管基于随机投影的LSH极其简单，但我们的结果表明，该算法的性能远远低估了。为了可重复性，本文使用的所有代码都在GitHub上发布，可以作为公平比较各种哈希算法的测试平台。

##### URL
[http://arxiv.org/abs/1612.07545](http://arxiv.org/abs/1612.07545)

##### PDF
[http://arxiv.org/pdf/1612.07545](http://arxiv.org/pdf/1612.07545)

