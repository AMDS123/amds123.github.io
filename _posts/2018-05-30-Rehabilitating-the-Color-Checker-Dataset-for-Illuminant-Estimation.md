---
layout: post
title: "Rehabilitating the Color Checker Dataset for Illuminant Estimation"
date: 2018-05-30 23:41:17
categories: arXiv_CV
tags: arXiv_CV Review Attention
author: Ghalia Hemrit, Graham D. Finlayson, Arjan Gijsenij, Peter Gehler, Simone Bianco, Mark Drew
mathjax: true
---

* content
{:toc}

##### Abstract
In a previous work, it was shown that there is a curious problem with the benchmark Color Checker dataset for illuminant estimation. To wit, this dataset has at least 3 different sets of ground-truths. Typically, for a single algorithm a single ground-truth is used. But then different algorithms, whose performance is measured with respect to different ground-truths, are compared against each other and then ranked. This makes no sense. In fact it is nonsense. We show in this paper that there are also errors in how each ground-truth set was calculated. As a result, all performance rankings based on the Color Checker dataset - and there are scores of these - are ill-founded. 
 In this paper, we re-generate a new 'recommended' set of ground-truth based on the calculation methodology described by Shi and Funt. We then review the performance evaluation of a range of illuminant estimation algorithms. Compared with the legacy ground-truths, we find that the difference in how algorithms perform can be large with many local rankings of algorithms being reversed. 
 Finally, we draw the readers attention to our new 'open' data repository which, we hope, will allow the Color Checker set to be rehabilitated and, once again, to become a useful benchmark for illuminant estimation algorithms.

##### Abstract (translated by Google)
在之前的工作中，它表明，用于光源估计的基准Color Checker数据集存在一个奇怪的问题。也就是说，这个数据集至少有3组不同的基本事实。通常，对于单个算法，使用单个地面实况。但是接下来比较不同的算法，它们的性能是根据不同的地面实况来衡量的，然后进行比较并排名。这没有意义。其实这是无稽之谈。我们在本文中表明，每个地面真值集的计算方式也存在错误。因此，基于Color Checker数据集的所有表现排名 - 以及其中的几十分 - 都是没有根据的。
 在本文中，我们根据Shi和Funt描述的计算方法重新生成一个新的“推荐”基础真实集合。然后，我们回顾一系列光源估计算法的性能评估。与传统的基本事实相比，我们发现算法执行方式的差异可能很大，因为许多本地算法排名颠倒了。
 最后，我们引起读者对我们新的“开放”数据存储库的关注，我们希望这将允许Color Checker集进行修复，并再次成为光源估计算法的有用基准。

##### URL
[http://arxiv.org/abs/1805.12262](http://arxiv.org/abs/1805.12262)

##### PDF
[http://arxiv.org/pdf/1805.12262](http://arxiv.org/pdf/1805.12262)

