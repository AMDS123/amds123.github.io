---
layout: post
title: "Rehabilitating the ColorChecker Dataset for Illuminant Estimation"
date: 2018-09-12 11:30:31
categories: arXiv_CV
tags: arXiv_CV Review Attention
author: Ghalia Hemrit, Graham D. Finlayson, Arjan Gijsenij, Peter Gehler, Simone Bianco, Brian Funt, Mark Drew, Lilong Shi
mathjax: true
---

* content
{:toc}

##### Abstract
In a previous work, it was shown that there is a curious problem with the benchmark ColorChecker dataset for illuminant estimation. To wit, this dataset has at least 3 different sets of ground-truths. Typically, for a single algorithm a single ground-truth is used. But then different algorithms, whose performance is measured with respect to different ground-truths, are compared against each other and then ranked. This makes no sense. We show in this paper that there are also errors in how each ground-truth set was calculated. As a result, all performance rankings based on the ColorChecker dataset - and there are scores of these - are inaccurate. 
 In this paper, we re-generate a new 'recommended' set of ground-truth based on the calculation methodology described by Shi and Funt. We then review the performance evaluation of a range of illuminant estimation algorithms. Compared with the legacy ground-truths, we find that the difference in how algorithms perform can be large, with many local rankings of algorithms being reversed. 
 Finally, we draw the readers attention to our new 'open' data repository which, we hope, will allow the ColorChecker set to be rehabilitated and once again to become a useful benchmark for illuminant estimation algorithms.

##### Abstract (translated by Google)
在之前的工作中，显示基准ColorChecker数据集存在奇怪的问题，用于光源估计。也就是说，该数据集至少有3组不同的基础事实。通常，对于单个算法，使用单个地面实况。但是，将不同的算法（其性能根据不同的真实性进行测量）相互比较，然后进行排序。这毫无意义。我们在本文中表明，每个地面实况集的计算方式也存在误差。因此，基于ColorChecker数据集的所有性能排名 - 以及其中的分数 - 都是不准确的。
 在本文中，我们基于Shi和Funt描述的计算方法重新生成一组新的“推荐的”基础事实。然后，我们回顾了一系列光源估算算法的性能评估。与传统的基础事实相比，我们发现算法执行方式的差异可能很大，许多本地算法排名都是相反的。
 最后，我们吸引读者注意我们新的“开放式”数据存储库，我们希望这将使ColorChecker集合得以恢复，并再次成为光源估算算法的有用基准。

##### URL
[http://arxiv.org/abs/1805.12262](http://arxiv.org/abs/1805.12262)

##### PDF
[http://arxiv.org/pdf/1805.12262](http://arxiv.org/pdf/1805.12262)

