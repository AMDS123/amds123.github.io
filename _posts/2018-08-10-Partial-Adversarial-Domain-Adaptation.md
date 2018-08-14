---
layout: post
title: "Partial Adversarial Domain Adaptation"
date: 2018-08-10 17:18:33
categories: arXiv_CV
tags: arXiv_CV Adversarial
author: Zhangjie Cao, Lijia Ma, Mingsheng Long, Jianmin Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Domain adversarial learning aligns the feature distributions across the source and target domains in a two-player minimax game. Existing domain adversarial networks generally assume identical label space across different domains. In the presence of big data, there is strong motivation of transferring deep models from existing big domains to unknown small domains. This paper introduces partial domain adaptation as a new domain adaptation scenario, which relaxes the fully shared label space assumption to that the source label space subsumes the target label space. Previous methods typically match the whole source domain to the target domain, which are vulnerable to negative transfer for the partial domain adaptation problem due to the large mismatch between label spaces. We present Partial Adversarial Domain Adaptation (PADA), which simultaneously alleviates negative transfer by down-weighing the data of outlier source classes for training both source classifier and domain adversary, and promotes positive transfer by matching the feature distributions in the shared label space. Experiments show that PADA exceeds state-of-the-art results for partial domain adaptation tasks on several datasets.

##### Abstract (translated by Google)
域对抗性学习在双人迷你游戏中对齐源域和目标域中的特征分布。现有域对抗性网络通常假设跨不同域的相同标签空间。在存在大数据的情况下，存在将深层模型从现有大域转移到未知小域的强烈动机。本文将部分域自适应作为一种新的域自适应场景，将完全共享的标签空间假设放宽为源标签空间包含目标标签空间。先前的方法通常将整个源域与目标域匹配，由于标签空间之间的大的不匹配，这些域易受到部分域适应问题的负转移的影响。我们提出了部分对抗域适应（PADA），它通过对异常源类的数据进行权重下调来同时减轻负转移，以便训练源分类器和域对手，并通过匹配共享标签空间中的特征分布来促进正转移。实验表明，PADA超过了几个数据集上部分域适应任务的最新结果。

##### URL
[http://arxiv.org/abs/1808.04205](http://arxiv.org/abs/1808.04205)

##### PDF
[http://arxiv.org/pdf/1808.04205](http://arxiv.org/pdf/1808.04205)

