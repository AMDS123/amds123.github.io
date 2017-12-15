---
layout: post
title: "Mapping Between fMRI Responses to Movies and their Natural Language Annotations"
date: 2017-04-10 08:41:51
categories: arXiv_CL
tags: arXiv_CL Embedding Classification
author: Kiran Vodrahalli, Po-Hsuan Chen, Yingyu Liang, Christopher Baldassano, Janice Chen, Esther Yong, Christopher Honey, Uri Hasson, Peter Ramadge, Ken Norman, Sanjeev Arora
mathjax: true
---

* content
{:toc}

##### Abstract
Several research groups have shown how to correlate fMRI responses to the meanings of presented stimuli. This paper presents new methods for doing so when only a natural language annotation is available as the description of the stimulus. We study fMRI data gathered from subjects watching an episode of BBCs Sherlock [1], and learn bidirectional mappings between fMRI responses and natural language representations. We show how to leverage data from multiple subjects watching the same movie to improve the accuracy of the mappings, allowing us to succeed at a scene classification task with 72% accuracy (random guessing would give 4%) and at a scene ranking task with average rank in the top 4% (random guessing would give 50%). The key ingredients are (a) the use of the Shared Response Model (SRM) and its variant SRM-ICA [2, 3] to aggregate fMRI data from multiple subjects, both of which are shown to be superior to standard PCA in producing low-dimensional representations for the tasks in this paper; (b) a sentence embedding technique adapted from the natural language processing (NLP) literature [4] that produces semantic vector representation of the annotations; (c) using previous timestep information in the featurization of the predictor data.

##### Abstract (translated by Google)
几个研究小组已经展示了如何将fMRI反应与所呈现的刺激的含义相关联。本文提出了当只有自然语言注释可用作为刺激的描述时这样做的新方法。我们研究从观看BBCs Sherlock [1]节目的受试者收集的fMRI数据，并学习fMRI反应与自然语言表征之间的双向映射。我们展示了如何利用来自多个主题的数据来观看相同的电影，以提高映射的准确性，使我们能够以72％的准确率（随机猜测将给出4％）在场景分类任务中成功并且在平均场景评级任务排在前4％（随机猜测会得到50％）。关键成分是（a）使用共享反应模型（SRM）及其变体SRM-ICA [2,3]来汇总来自多个受试者的fMRI数据，两者在产生低水平时显示优于标准PCA本文中任务的三维表示; （b）从自然语言处理（NLP）文献[4]改编的句子嵌入技术，其产生注释的语义向量表示; （c）在预测数据的特征化中使用先前的时间步骤信息。

##### URL
[https://arxiv.org/abs/1610.03914](https://arxiv.org/abs/1610.03914)

##### PDF
[https://arxiv.org/pdf/1610.03914](https://arxiv.org/pdf/1610.03914)

