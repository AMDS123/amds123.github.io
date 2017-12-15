---
layout: post
title: "Improving Information Extraction by Acquiring External Evidence with Reinforcement Learning"
date: 2016-09-27 23:33:28
categories: arXiv_SD
tags: arXiv_SD Reinforcement_Learning
author: Karthik Narasimhan, Adam Yala, Regina Barzilay
mathjax: true
---

* content
{:toc}

##### Abstract
Most successful information extraction systems operate with access to a large collection of documents. In this work, we explore the task of acquiring and incorporating external evidence to improve extraction accuracy in domains where the amount of training data is scarce. This process entails issuing search queries, extraction from new sources and reconciliation of extracted values, which are repeated until sufficient evidence is collected. We approach the problem using a reinforcement learning framework where our model learns to select optimal actions based on contextual information. We employ a deep Q-network, trained to optimize a reward function that reflects extraction accuracy while penalizing extra effort. Our experiments on two databases -- of shooting incidents, and food adulteration cases -- demonstrate that our system significantly outperforms traditional extractors and a competitive meta-classifier baseline.

##### Abstract (translated by Google)
大多数成功的信息提取系统都可以访问大量的文件。在这项工作中，我们探索获取和整合外部证据的任务，以提高在训练数据量很少的领域的提取准确性。这个过程需要发出搜索查询，从新的来源提取和提取值的对帐，重复这个过程直到收集到足够的证据。我们使用强化学习框架来处理这个问题，在这个框架中，我们的模型学习根据上下文信息来选择最优的行为。我们采用深度Q网络，训练优化奖励功能，反映提取精度，同时惩罚额外的努力。我们在两个数据库 - 射击事件和食品掺假案例 - 上的实验表明，我们的系统明显优于传统提取器和竞争性元分类器基线。

##### URL
[https://arxiv.org/abs/1603.07954](https://arxiv.org/abs/1603.07954)

##### PDF
[https://arxiv.org/pdf/1603.07954](https://arxiv.org/pdf/1603.07954)

