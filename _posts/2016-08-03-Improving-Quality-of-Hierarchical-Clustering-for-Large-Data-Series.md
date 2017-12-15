---
layout: post
title: "Improving Quality of Hierarchical Clustering for Large Data Series"
date: 2016-08-03 16:12:23
categories: arXiv_CL
tags: arXiv_CL Optimization Language_Model
author: Manuel R. Ciosici
mathjax: true
---

* content
{:toc}

##### Abstract
Brown clustering is a hard, hierarchical, bottom-up clustering of words in a vocabulary. Words are assigned to clusters based on their usage pattern in a given corpus. The resulting clusters and hierarchical structure can be used in constructing class-based language models and for generating features to be used in NLP tasks. Because of its high computational cost, the most-used version of Brown clustering is a greedy algorithm that uses a window to restrict its search space. Like other clustering algorithms, Brown clustering finds a sub-optimal, but nonetheless effective, mapping of words to clusters. Because of its ability to produce high-quality, human-understandable cluster, Brown clustering has seen high uptake the NLP research community where it is used in the preprocessing and feature generation steps. Little research has been done towards improving the quality of Brown clusters, despite the greedy and heuristic nature of the algorithm. The approaches tried so far have focused on: studying the effect of the initialisation in a similar algorithm; tuning the parameters used to define the desired number of clusters and the behaviour of the algorithm; and including a separate parameter to differentiate the window from the desired number of clusters. However, some of these approaches have not yielded significant improvements in cluster quality. In this thesis, a close analysis of the Brown algorithm is provided, revealing important under-specifications and weaknesses in the original algorithm. These have serious effects on cluster quality and reproducibility of research using Brown clustering. In the second part of the thesis, two modifications are proposed. Finally, a thorough evaluation is performed, considering both the optimization criterion of Brown clustering and the performance of the resulting class-based language models.

##### Abstract (translated by Google)
布朗聚类是词汇中词汇的一种艰难的，等级的，自下而上的聚类。根据给定语料库中的使用模式将词分配给聚类。由此产生的聚类和层次结构可以用于构建基于类的语言模型，以及用于生成要在NLP任务中使用的特征。由于其高计算成本，布朗聚类最常用的版本是一个贪婪的算法，它使用一个窗口来限制其搜索空间。像其他聚类算法一样，布朗聚类找到一个次优的，但仍然有效的词映射到聚类。由于其能够生成高质量，可理解的群集，Brown聚类已经被NLP研究团队高度推广，并被用于预处理和特征生成步骤。尽管算法的贪婪性和启发性本质，但对于提高布朗组质量的研究却很少。到目前为止所尝试的方法主要集中在：研究类似算法中初始化的影响;调整用于定义所需数量的簇和参数的行为的参数;并包括一个单独的参数来区分窗口与所需数量的簇。但是，其中一些方法在集群质量方面没有取得显着的改进。本文对Brown算法进行了详细的分析，揭示了原算法中的重要规范和弱点。这些对集群质量和使用Brown聚类的研究的可重复性有严重的影响。在论文的第二部分，提出了两个修改。最后，考虑布朗聚类的优化准则以及由此产生的基于类的语言模型的性能，进行彻底的评估。

##### URL
[https://arxiv.org/abs/1608.01238](https://arxiv.org/abs/1608.01238)

##### PDF
[https://arxiv.org/pdf/1608.01238](https://arxiv.org/pdf/1608.01238)

