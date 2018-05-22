---
layout: post
title: "AlphaX: eXploring Neural Architectures with Deep Neural Networks and Monte Carlo Tree Search"
date: 2018-05-18 20:57:41
categories: arXiv_AI
tags: arXiv_AI
author: Linnan Wang, Yiyang Zhao, Yuu Jinnai
mathjax: true
---

* content
{:toc}

##### Abstract
We present AlphaX, a fully automated agent that designs complex neural architectures from scratch. AlphaX explores the exponentially exploded search space with a novel distributed Monte Carlo Tree Search (MCTS) and a Meta-Deep Neural Network (DNN). MCTS intrinsically improves the search efficiency by automatically balancing the exploration and exploitation at each state, while Meta-DNN predicts the network accuracy to guide the search, and to provide an estimated reward for the preemptive backpropagation in the distributed setup. As the search progresses, AlphaX also generates the training date for Meta-DNN. So, the learning of Meta-DNN is end-to-end. In searching for NASNet style architectures, AlphaX found several promising architectures with up to 1% higher accuracy than NASNet using only 17 GPUs for 5 days, demonstrating up to 23.5x speedup over the original searching for NASNet that used 500 GPUs in 4 days.

##### Abstract (translated by Google)
我们提供AlphaX，一个全自动代理，从头开始设计复杂的神经架构。 AlphaX利用新型分布式蒙特卡罗树搜索（MCTS）和元深度神经网络（DNN）探索指数分解搜索空间。 MCTS通过自动平衡每个州的探索和利用来本质上提高搜索效率，而Meta-DNN预测网络准确性以指导搜索，并为分布式设置中的抢先式反向传播提供估计奖励。随着搜索的进行，AlphaX还会生成Meta-DNN的培训日期。所以，Meta-DNN的学习是端到端的。在寻找NASNet风格的体系结构时，AlphaX发现了几个有前景的架构，其精度比NASNet高出1％，仅使用17个GPU 5天，相比于原先在4天内使用500个GPU的NASNet搜索，速度提高了23.5倍。

##### URL
[https://arxiv.org/abs/1805.07440](https://arxiv.org/abs/1805.07440)

##### PDF
[https://arxiv.org/pdf/1805.07440](https://arxiv.org/pdf/1805.07440)

