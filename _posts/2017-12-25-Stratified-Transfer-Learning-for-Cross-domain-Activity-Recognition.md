---
layout: post
title: "Stratified Transfer Learning for Cross-domain Activity Recognition"
date: 2017-12-25 06:18:31
categories: arXiv_CV
tags: arXiv_CV Knowledge Transfer_Learning Classification Recognition
author: Jindong Wang, Yiqiang Chen, Lisha Hu, Xiaohui Peng, Philip S. Yu
mathjax: true
---

* content
{:toc}

##### Abstract
In activity recognition, it is often expensive and time-consuming to acquire sufficient activity labels. To solve this problem, transfer learning leverages the labeled samples from the source domain to annotate the target domain which has few or none labels. Existing approaches typically consider learning a global domain shift while ignoring the intra-affinity between classes, which will hinder the performance of the algorithms. In this paper, we propose a novel and general cross-domain learning framework that can exploit the intra-affinity of classes to perform intra-class knowledge transfer. The proposed framework, referred to as Stratified Transfer Learning (STL), can dramatically improve the classification accuracy for cross-domain activity recognition. Specifically, STL first obtains pseudo labels for the target domain via majority voting technique. Then, it performs intra-class knowledge transfer iteratively to transform both domains into the same subspaces. Finally, the labels of target domain are obtained via the second annotation. To evaluate the performance of STL, we conduct comprehensive experiments on three large public activity recognition datasets~(i.e. OPPORTUNITY, PAMAP2, and UCI DSADS), which demonstrates that STL significantly outperforms other state-of-the-art methods w.r.t. classification accuracy (improvement of 7.68%). Furthermore, we extensively investigate the performance of STL across different degrees of similarities and activity levels between domains. And we also discuss the potential of STL in other pervasive computing applications to provide empirical experience for future research.

##### Abstract (translated by Google)
在活动识别中，获取足够的活动标签往往是昂贵和耗时的。为了解决这个问题，转移学习利用来自源域的标记样本来注释具有很少或没有标签的目标域。现有的方法通常考虑学习一个全局的域转换，而忽略了类之间的内部关联，这将阻碍算法的性能。在本文中，我们提出了一个新的，通用的跨领域学习框架，可以利用类的内部亲和力来进行课内知识转移。所提出的框架被称为分层转移学习（STL），可以显着提高跨域活动识别的分类准确性。具体来说，STL首先通过多数投票技术获得目标域的伪标签。然后，它迭代执行类内知识转移，将两个域转换为相同的子空间。最后，通过第二个注释获得目标域的标签。为了评估STL的性能，我们对三个大型公共活动识别数据集（即OPPORTUNITY，PAMAP2和UCI DSADS）进行了全面的实验，结果表明STL明显优于其他最先进的方法w.r.t.分类准确率（提高7.68％）。此外，我们广泛调查STL在不同程度的相似性和域间活动水平上的表现。同时我们也讨论了STL在其他普适计算应用中的潜力，为今后的研究提供实证经验。

##### URL
[http://arxiv.org/abs/1801.00820](http://arxiv.org/abs/1801.00820)

##### PDF
[http://arxiv.org/pdf/1801.00820](http://arxiv.org/pdf/1801.00820)

