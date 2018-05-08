---
layout: post
title: "Weakly-supervised Contextualization of Knowledge Graph Facts"
date: 2018-05-07 08:22:57
categories: arXiv_AI
tags: arXiv_AI Knowledge_Graph Knowledge Relation
author: Nikos Voskarides, Edgar Meij, Ridho Reinanda, Abhinav Khaitan, Miles Osborne, Giorgio Stefanoni, Prabhanjan Kambadur, Maarten de Rijke
mathjax: true
---

* content
{:toc}

##### Abstract
Knowledge graphs (KGs) model facts about the world, they consist of nodes (entities such as companies and people) that are connected by edges (relations such as founderOf). Facts encoded in KGs are frequently used by search applications to augment result pages. When presenting a KG fact to the user, providing other facts that are pertinent to that main fact can enrich the user experience and support exploratory information needs. KG fact contextualization is the task of augmenting a given KG fact with additional and useful KG facts. The task is challenging because of the large size of KGs, discovering other relevant facts even in a small neighborhood of the given fact results in an enormous amount of candidates. We introduce a neural fact contextualization method (NFCM) to address the KG fact contextualization task. NFCM first generates a set of candidate facts in the neighborhood of a given fact and then ranks the candidate facts using a supervised learning to rank model. The ranking model combines features that we automatically learn from data and that represent the query-candidate facts with a set of hand-crafted features we devised or adjusted for this task. In order to obtain the annotations required to train the learning to rank model at scale, we generate training data automatically using distant supervision on a large entity-tagged text corpus. We show that ranking functions learned on this data are effective at contextualizing KG facts. Evaluation using human assessors shows that it significantly outperforms several competitive baselines.

##### Abstract (translated by Google)
知识图（KGs）模拟世界的事实，它们由通过边缘连接的节点（诸如公司和人的实体）组成（诸如founderOf之类的关系）。由KG编码的事实经常被搜索应用程序用来扩充结果页面。向用户提供KG事实时，提供与该主要事实相关的其他事实可以丰富用户体验并支持探索性信息需求。 KG事实情境化是通过增加有用的KG事实来增加给定的KG事实的任务。由于幼稚园规模庞大，甚至在一个小规模的邻居中发现其他相关的事实，结果造成了大量的候选人，因此这项任务具有挑战性。我们引入神经事实情境化方法（NFCM）来解决KG事实情境化任务。 NFCM首先在一个给定的事实的邻域内生成一组候选事实，然后使用监督学习对候选事实进行排序以排序模型。排名模型结合了我们自动从数据中学习的功能，并将查询候选事实与我们为此任务设计或调整的一组手工功能相结合。为了获得训练学习所需的注释以便按比例排列模型，我们使用远程监控对大型实体标记的文本语料库自动生成训练数据。我们表明，根据这些数据学到的排名功能在KG事实背景下是有效的。使用人力评估员进行评估表明，它显着优于几个竞争基线。

##### URL
[https://arxiv.org/abs/1805.02393](https://arxiv.org/abs/1805.02393)

##### PDF
[https://arxiv.org/pdf/1805.02393](https://arxiv.org/pdf/1805.02393)

