---
layout: post
title: "Probabilistic Semantic Retrieval for Surveillance Videos with Activity Graphs"
date: 2017-12-17 23:11:28
categories: arXiv_CL
tags: arXiv_CL Classification Detection Relation
author: Yuting Chen, Joseph Wang, Yannan Bai, Gregory Casta&#xf1;&#xf3;n, Venkatesh Saligrama
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel framework for finding complex activities matching user-described queries in cluttered surveillance videos. The wide diversity of queries coupled with unavailability of annotated activity data limits our ability to train activity models. To bridge the semantic gap we propose to let users describe an activity as a semantic graph with object attributes and inter-object relationships associated with nodes and edges, respectively. We learn node/edge-level visual predictors during training and, at test-time, propose to retrieve activity by identifying likely locations that match the semantic graph. We formulate a novel CRF based probabilistic activity localization objective that accounts for mis-detections, mis-classifications and track-losses, and outputs a likelihood score for a candidate grounded location of the query in the video. We seek groundings that maximize overall precision and recall. To handle the combinatorial search over all high-probability groundings, we propose a highest precision subtree algorithm. Our method outperforms existing retrieval methods on benchmarked datasets.

##### Abstract (translated by Google)
我们提出了一个新颖的框架，用于在杂乱的监视视频中查找与用户描述的查询匹配的复杂活动。查询的广泛多样性以及注释活动数据的不可用性限制了我们培训活动模型的能力。为了消除语义鸿沟，我们建议让用户将活动描述为一个语义图，分别使用与节点和边相关联的对象属性和对象间关系。我们在训练期间学习节点/边缘级视觉预测器，并且在测试时，通过识别与语义图匹配的可能位置来提议检索活动。我们制定了一个新的基于CRF的概率活动本地化目标，解释错误检测，错误分类和跟踪损失，并输出视频中候选基础位置的可能性分数。我们寻求最大限度地提高整体精度和召回的基础。为了处理所有高概率的基础上的组合搜索，我们提出了一个最高精度的子树算法。我们的方法在基准数据集上胜过现有的检索方法。

##### URL
[http://arxiv.org/abs/1712.06204](http://arxiv.org/abs/1712.06204)

##### PDF
[http://arxiv.org/pdf/1712.06204](http://arxiv.org/pdf/1712.06204)

