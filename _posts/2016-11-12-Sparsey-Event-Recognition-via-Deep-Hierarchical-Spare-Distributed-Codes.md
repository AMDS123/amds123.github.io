---
layout: post
title: "Sparsey: Event Recognition via Deep Hierarchical Spare Distributed Codes"
date: 2016-11-12 17:35:23
categories: arXiv_CV
tags: arXiv_CV Sparse GAN Inference Recognition
author: Gerard J. Rinkus
mathjax: true
---

* content
{:toc}

##### Abstract
Visual cortex's hierarchical, multi-level organization is captured in many biologically inspired computational vision models, the general idea being that progressively larger scale, more complex spatiotemporal features are represented in progressively higher areas. However, most earlier models use localist representations (codes) in each representational field, which we equate with the cortical macrocolumn (mac), at each level. In localism, each represented feature/event (item) is coded by a single unit. Our model, Sparsey, is also hierarchical but crucially, uses sparse distributed coding (SDC) in every mac in all levels. In SDC, each represented item is coded by a small subset of the mac's units. SDCs of different items can overlap and the size of overlap between items can represent their similarity. The difference between localism and SDC is crucial because SDC allows the two essential operations of associative memory, storing a new item and retrieving the best-matching stored item, to be done in fixed time for the life of the model. Since the model's core algorithm, which does both storage and retrieval (inference), makes a single pass over all macs on each time step, the overall model's storage/retrieval operation is also fixed-time, a criterion we consider essential for scalability to huge datasets. A 2010 paper described a nonhierarchical version of this model in the context of purely spatial pattern processing. Here, we elaborate a fully hierarchical model (arbitrary numbers of levels and macs per level), describing novel model principles like progressive critical periods, dynamic modulation of principal cells' activation functions based on a mac-level familiarity measure, representation of multiple simultaneously active hypotheses, a novel method of time warp invariant recognition, and we report results showing learning/recognition of spatiotemporal patterns.

##### Abstract (translated by Google)
视觉皮层的多层次，多层次的组织被许多具有生物启发性的计算视觉模型所捕获，总体思路是越来越大的范围，越来越大规模，更复杂的时空特征。然而，大多数早期的模型在每个代表性领域都使用了地方主义代表（代码），我们在每个级别上都与皮层宏观科学专业（mac）相当。在地方主义中，每个代表的特征/事件（项目）都是由一个单元编码的。我们的模型，Sparsey，也是分层次的，但关键的是，在所有层次的每个MAC中使用稀疏分布式编码（SDC）。在SDC中，每个表示的项目是由mac的单位的一个小子集编码。不同项目的SDC可以重叠，项目之间重叠的大小可以表示它们的相似性。地方主义与SDC之间的差异是至关重要的，因为SDC允许联想记忆的两个基本操作，存储一个新的项目，并检索最匹配的存储项目，在模型的生命周期中进行固定的时间。既然存储和检索（推理）的模型的核心算法在每个时间步骤上对所有的mac进行一次遍历，整个模型的存储/检索操作也是固定时间的，这是我们认为对于可扩展性至关重要的一个标准数据集。 2010年的一篇论文描述了在纯空间模式处理的背景下这个模型的非层次版本。在这里，我们详细阐述了一个完全分层的模型（任意级别和每个级别的mac），描述了新的模型原则，如渐进关键时期，主体细胞激活函数的动态调节基于一个mac级别的熟悉度量，多个同时活动假设，一种新的时间扭曲不变式识别方法，我们报告的结果显示学习/识别的时空模式。

##### URL
[https://arxiv.org/abs/1611.04023](https://arxiv.org/abs/1611.04023)

##### PDF
[https://arxiv.org/pdf/1611.04023](https://arxiv.org/pdf/1611.04023)

