---
layout: post
title: "Learning to Advertise with Adaptive Exposure via Constrained Two-Level Reinforcement Learning"
date: 2018-09-10 06:15:42
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Optimization Recommendation
author: Weixun Wang, Junqi Jin, Jianye Hao, Chunjie Chen, Chuan Yu, Weinan Zhang, Jun Wang, Yixi Wang, Han Li, Jian Xu, Kun Gai
mathjax: true
---

* content
{:toc}

##### Abstract
For online advertising in e-commerce, the traditional problem is to assign the right ad to the right user on fixed ad slots. In this paper, we investigate the problem of advertising with adaptive exposure, in which the number of ad slots and their locations can dynamically change over time based on their relative scores with recommendation products. In order to maintain user retention and long-term revenue, there are two types of constraints that need to be met in exposure: query-level and day-level constraints. We model this problem as constrained markov decision process with per-state constraint (psCMDP) and propose a constrained two-level reinforcement learning to decouple the original advertising exposure optimization problem into two relatively independent sub-optimization problems. We also propose a constrained hindsight experience replay mechanism to accelerate the policy training process. Experimental results show that our method can improve the advertising revenue while satisfying different levels of constraints under the real-world datasets. Besides, the proposal of constrained hindsight experience replay mechanism can significantly improve the training speed and the stability of policy performance.

##### Abstract (translated by Google)
对于电子商务中的在线广告，传统的问题是在固定广告位上为正确的用户分配正确的广告。在本文中，我们研究了自适应曝光广告的问题，其中广告位的数量及其位置可以根据其与推荐产品的相对分数随时间动态变化。为了保持用户保留和长期收入，在暴露中需要满足两种类型的约束：查询级别和日级约束。我们将此问题建模为具有每状态约束（psCMDP）的约束马尔可夫决策过程，并提出约束的两级强化学习以将原始广告暴露优化问题分解为两个相对独立的子优化问题。我们还提出了一个受约束的事后体验重播机制来加速政策培训过程。实验结果表明，我们的方法可以在满足现实世界数据集的不同约束条件的同时提高广告收入。此外，约束事后经验重建机制的提议可以显着提高培训速度和政策绩效的稳定性。

##### URL
[http://arxiv.org/abs/1809.03149](http://arxiv.org/abs/1809.03149)

##### PDF
[http://arxiv.org/pdf/1809.03149](http://arxiv.org/pdf/1809.03149)

