---
layout: post
title: "Multi-Perspective Context Aggregation for Semi-supervised Cloze-style Reading Comprehension"
date: 2018-08-20 02:36:55
categories: arXiv_CL
tags: arXiv_CL
author: Liang Wang, Sujian Li, Wei Zhao, Kewei Shen, Meng Sun, Ruoyu Jia, Jingming Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Cloze-style reading comprehension has been a popular task for measuring the progress of natural language understanding in recent years. In this paper, we design a novel multi-perspective framework, which can be seen as the joint training of heterogeneous experts and aggregate context information from different perspectives. Each perspective is modeled by a simple aggregation module. The outputs of multiple aggregation modules are fed into a one-timestep pointer network to get the final answer. At the same time, to tackle the problem of insufficient labeled data, we propose an efficient sampling mechanism to automatically generate more training examples by matching the distribution of candidates between labeled and unlabeled data. We conduct our experiments on a recently released cloze-test dataset CLOTH (Xie et al., 2017), which consists of nearly 100k questions designed by professional teachers. Results show that our method achieves new state-of-the-art performance over previous strong baselines.

##### Abstract (translated by Google)
完形填空式的阅读理解一直是衡量近年来自然语言理解进程的一项流行任务。在本文中，我们设计了一个新的多视角框架，可以看作是异构专家的联合培训和不同视角下的聚合上下文信息。每个透视图都由一个简单的聚合模块建模。多个聚合模块的输出被馈送到一个一步指针网络以获得最终答案。同时，为了解决标签数据不足的问题，我们提出了一种有效的采样机制，通过匹配标记数据和未标记数据之间的候选分布来自动生成更多训练样例。我们在最近发布的完形填空测试数据集CLOTH（Xie et al。，2017）上进行实验，其中包括由专业教师设计的近10万个问题。结果表明，我们的方法比以前的强基线实现了新的最先进的性能。

##### URL
[http://arxiv.org/abs/1808.06289](http://arxiv.org/abs/1808.06289)

##### PDF
[http://arxiv.org/pdf/1808.06289](http://arxiv.org/pdf/1808.06289)

