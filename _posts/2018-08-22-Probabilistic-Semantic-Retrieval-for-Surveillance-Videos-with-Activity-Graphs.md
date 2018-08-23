---
layout: post
title: "Probabilistic Semantic Retrieval for Surveillance Videos with Activity Graphs"
date: 2018-08-22 02:03:27
categories: arXiv_CL
tags: arXiv_CL Classification Detection Relation
author: Yuting Chen, Joseph Wang, Yannan Bai, Gregory Casta&#xf1;&#xf3;n, Venkatesh Saligrama
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel framework for finding complex activities matching user-described queries in cluttered surveillance videos. The wide diversity of queries coupled with unavailability of annotated activity data limits our ability to train activity models. To bridge the semantic gap we propose to let users describe an activity as a semantic graph with object attributes and inter-object relationships associated with nodes and edges, respectively. We learn node/edge-level visual predictors during training and, at test-time, propose to retrieve activity by identifying likely locations that match the semantic graph. We formulate a novel CRF based probabilistic activity localization objective that accounts for mis-detections, mis-classifications and track-losses, and outputs a likelihood score for a candidate grounded location of the query in the video. We seek groundings that maximize overall precision and recall. To handle the combinatorial search over all high-probability groundings, we propose a highest precision subgraph matching algorithm. Our method outperforms existing retrieval methods on benchmarked datasets.

##### Abstract (translated by Google)
我们提出了一个新的框架，用于在杂乱的监控视频中查找与用户描述的查询相匹配的复杂活动。查询的多样性加上注释活动数据的不可用性限制了我们训练活动模型的能力。为了弥合语义鸿沟，我们建议让用户将活动描述为具有对象属性和与节点和边缘相关联的对象间关系的语义图。我们在训练期间学习节点/边缘级视觉预测器，并且在测试时，建议通过识别与语义图匹配的可能位置来检索活动。我们制定了一种新颖的基于CRF的概率活动本地化目标，该目标考虑了错误检测，错误分类和跟踪损失，并输出了视频中查询的候选基础位置的似然分数。我们寻求最大化整体精确度和召回率的基础。为了处理所有高概率基础上的组合搜索，我们提出了一种最高精度的子图匹配算法。我们的方法优于基准数据集上的现有检索方法。

##### URL
[http://arxiv.org/abs/1712.06204](http://arxiv.org/abs/1712.06204)

##### PDF
[http://arxiv.org/pdf/1712.06204](http://arxiv.org/pdf/1712.06204)

