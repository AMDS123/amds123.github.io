---
layout: post
title: "Collective Entity Disambiguation with Structured Gradient Tree Boosting"
date: 2018-02-28 02:01:30
categories: arXiv_CL
tags: arXiv_CL Knowledge Inference Classification
author: Yi Yang, Ozan Irsoy, Kazi Shefaet Rahman
mathjax: true
---

* content
{:toc}

##### Abstract
We present a gradient-tree-boosting-based structured learning model for jointly disambiguating named entities in a document. Gradient tree boosting is a widely used machine learning algorithm that underlies many top-performing natural language processing systems. Surprisingly, most works limit the use of gradient tree boosting as a tool for regular classification or regression problems, despite the structured nature of language. To the best of our knowledge, our work is the first one that employs the structured gradient tree boosting (SGTB) algorithm for collective entity disambiguation. By defining global features over previous disambiguation decisions and jointly modeling them with local features, our system is able to produce globally optimized entity assignments for mentions in a document. Exact inference is prohibitively expensive for our globally normalized model. To solve this problem, we propose Bidirectional Beam Search with Gold path (BiBSG), an approximate inference algorithm that is a variant of the standard beam search algorithm. BiBSG makes use of global information from both past and future to perform better local search. Experiments on standard benchmark datasets show that SGTB significantly improves upon published results. Specifically, SGTB outperforms the previous state-of-the-art neural system by near 1\% absolute accuracy on the popular AIDA-CoNLL dataset.

##### Abstract (translated by Google)
我们提出了一个基于梯度树的增强型结构化学习模型，用于联合消除文档中命名实体的歧义。梯度树提升是一种广泛使用的机器学习算法，是许多高性能自然语言处理系统的基础。令人惊讶的是，尽管语言具有结构化的性质，但大多数作品限制使用渐变树增强作为常规分类或回归问题的工具。就我们所知，我们的工作是第一个采用结构化梯度树增强（SGTB）算法进行集体实体消歧的工作。通过在先前的消歧决策中定义全局特征并与局部特征联合建模，我们的系统能够针对文档中的提及产生全局优化的实体指派。对于我们的全球标准化模型而言，精确的推断过于昂贵。为了解决这个问题，我们提出了带有Gold路径的双向光束搜索（BiBSG），这是一种近似推理算法，它是标准光束搜索算法的变体。 BiBSG利用过去和未来的全球信息来执行更好的本地搜索。标准基准数据集的实验表明，SGTB显着提高了公布的结果。具体来说，SGTB在流行的AIDA-CoNLL数据集上的表现优于先前的先进神经系统，接近1％的绝对精度。

##### URL
[http://arxiv.org/abs/1802.10229](http://arxiv.org/abs/1802.10229)

##### PDF
[http://arxiv.org/pdf/1802.10229](http://arxiv.org/pdf/1802.10229)

