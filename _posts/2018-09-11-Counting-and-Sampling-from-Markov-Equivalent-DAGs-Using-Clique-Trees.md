---
layout: post
title: "Counting and Sampling from Markov Equivalent DAGs Using Clique Trees"
date: 2018-09-11 01:49:04
categories: arXiv_AI
tags: arXiv_AI Knowledge Inference Relation
author: AmirEmad Ghassami, Saber Salehkaleybar, Negar Kiyavash, Kun Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
A directed acyclic graph (DAG) is the most common graphical model for representing causal relationships among a set of variables. When restricted to using only observational data, the structure of the ground truth DAG is identifiable only up to Markov equivalence, based on conditional independence relations among the variables. Therefore, the number of DAGs equivalent to the ground truth DAG is an indicator of the causal complexity of the underlying structure--roughly speaking, it shows how many interventions or how much additional information is further needed to recover the underlying DAG. In this paper, we propose a new technique for counting the number of DAGs in a Markov equivalence class. Our approach is based on the clique tree representation of chordal graphs. We show that in the case of bounded degree graphs, the proposed algorithm is polynomial time. We further demonstrate that this technique can be utilized for uniform sampling from a Markov equivalence class, which provides a stochastic way to enumerate DAGs in the equivalence class and may be needed for finding the best DAG or for causal inference given the equivalence class as input. We also extend our counting and sampling method to the case where prior knowledge about the underlying DAG is available, and present applications of this extension in causal experiment design and estimating the causal effect of joint interventions.

##### Abstract (translated by Google)
有向无环图（DAG）是用于表示一组变量之间的因果关系的最常见的图形模型。当仅限于使用观测数据时，基于变量之间的条件独立关系，地面实况DAG的结构仅可识别达马尔可夫等价。因此，与基础事实DAG相当的DAG数量是基础结构因果复杂性的指标 - 粗略地说，它显示了恢复基础DAG需要多少次干预或需要多少额外信息。在本文中，我们提出了一种计算马尔可夫等价类中DAG数量的新技术。我们的方法基于弦图的clique树表示。我们证明了在有界度图的情况下，所提出的算法是多项式时间。我们进一步证明了这种技术可以用于马尔可夫等价类的均匀采样，它提供了一种随机方法来枚举等价类中的DAG，并且可能需要找到最佳DAG或者在等价类作为输入的情况下进行因果推断。我们还将计数和抽样方法扩展到可获得关于基础DAG的先验知识的情况，并将此扩展的应用呈现在因果实验设计中并估计联合干预的因果效应。

##### URL
[http://arxiv.org/abs/1802.01239](http://arxiv.org/abs/1802.01239)

##### PDF
[http://arxiv.org/pdf/1802.01239](http://arxiv.org/pdf/1802.01239)

