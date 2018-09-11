---
layout: post
title: "Rebalancing Dockless Bike Sharing Systems"
date: 2018-09-10 15:57:01
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Optimization Prediction
author: Ling Pan, Qingpeng Cai, Zhixuan Fang, Pingzhong Tang, Longbo Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Bike sharing provides an environment-friendly way for traveling and is booming all over the world. Yet, due to the high similarity of user travel patterns, the bike imbalance problem constantly occurs, especially for dockless bike sharing systems, causing significant impact on service quality and company revenue. Thus, it has become a critical task for bike sharing systems to resolve such imbalance efficiently. In this paper, we propose a novel deep reinforcement learning framework for incentivizing users to rebalance such systems. We model the problem as a Markov decision process and take both spatial and temporal features into consideration. We develop a novel deep reinforcement learning algorithm called Hierarchical Reinforcement Pricing (HRP), which builds upon the Deep Deterministic Policy Gradient algorithm. Different from existing methods that often ignore spatial information and rely heavily on accurate prediction, HRP captures both spatial and temporal dependencies using a divide-and-conquer structure with an embedded localized module. We conduct extensive experiments to evaluate HRP, based on a dataset from Mobike, a major Chinese dockless bike sharing company. Results show that HRP performs close to the 24-timeslot look-ahead optimization, and outperforms state-of-the-art methods in both service level and bike distribution. It also transfers well when applied to unseen areas.

##### Abstract (translated by Google)
自行车共享提供了一种环保的旅行方式，并在世界各地蓬勃发展。然而，由于用户旅行模式的高度相似性，自行车不平衡问题不断发生，特别是对于无码头自行车共享系统，对服务质量和公司收入造成重大影响。因此，自行车共享系统有效地解决这种不平衡已成为一项关键任务。在本文中，我们提出了一种新的深度强化学习框架，用于激励用户重新平衡这些系统。我们将问题建模为马尔可夫决策过程，并考虑空间和时间特征。我们开发了一种新的深度强化学习算法，称为分层强化定价（HRP），它基于深度确定性策略梯度算法。与通常忽略空间信息并严重依赖于准确预测的现有方法不同，HRP使用具有嵌入式本地化模块的分而治之结构来捕获空间和时间依赖性。我们基于Mobike的数据集进行了大量的实验来评估HRP，Mobike是一家主要的中国无人自行车共享公司。结果表明，HRP接近24时隙前瞻优化，在服务水平和自行车分布方面均优于最先进的方法。当应用于看不见的区域时，它也可以很好地传输。

##### URL
[http://arxiv.org/abs/1802.04592](http://arxiv.org/abs/1802.04592)

##### PDF
[http://arxiv.org/pdf/1802.04592](http://arxiv.org/pdf/1802.04592)

