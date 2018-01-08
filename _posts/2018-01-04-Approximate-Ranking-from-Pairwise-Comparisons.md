---
layout: post
title: "Approximate Ranking from Pairwise Comparisons"
date: 2018-01-04 06:18:39
categories: arXiv_AI
tags: arXiv_AI
author: Reinhard Heckel, Max Simchowitz, Kannan Ramchandran, Martin J. Wainwright
mathjax: true
---

* content
{:toc}

##### Abstract
A common problem in machine learning is to rank a set of n items based on pairwise comparisons. Here ranking refers to partitioning the items into sets of pre-specified sizes according to their scores, which includes identification of the top-k items as the most prominent special case. The score of a given item is defined as the probability that it beats a randomly chosen other item. Finding an exact ranking typically requires a prohibitively large number of comparisons, but in practice, approximate rankings are often adequate. Accordingly, we study the problem of finding approximate rankings from pairwise comparisons. We analyze an active ranking algorithm that counts the number of comparisons won, and decides whether to stop or which pair of items to compare next, based on confidence intervals computed from the data collected in previous steps. We show that this algorithm succeeds in recovering approximate rankings using a number of comparisons that is close to optimal up to logarithmic factors. We also present numerical results, showing that in practice, approximation can drastically reduce the number of comparisons required to estimate a ranking.

##### Abstract (translated by Google)
机器学习中的一个常见问题是根据成对比较对一组n项进行排序。这里的排名是指根据项目的得分将项目划分为预先确定的规模集合，其中包括最重要的特殊情况。给定项目的分数被定义为它击败随机选择的其他项目的概率。找到一个确切的排名通常需要大量的比较，但实际上，大致的排名往往是足够的。因此，我们研究从配对比较中找出近似排名的问题。我们分析一个有效的排名算法，对获胜的比较数进行计数，根据前面步骤收集的数据计算出的置信区间，决定是停止还是停止比较哪一对。我们表明，这个算法成功地恢复近似的排名使用一些比较接近最优的对数因子。我们还给出了数值结果，表明在实践中，近似可以大大减少估计排名所需的比较次数。

##### URL
[http://arxiv.org/abs/1801.01253](http://arxiv.org/abs/1801.01253)

##### PDF
[http://arxiv.org/pdf/1801.01253](http://arxiv.org/pdf/1801.01253)

