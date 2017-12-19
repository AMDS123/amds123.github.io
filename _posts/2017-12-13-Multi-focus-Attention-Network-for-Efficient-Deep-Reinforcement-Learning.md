---
layout: post
title: "Multi-focus Attention Network for Efficient Deep Reinforcement Learning"
date: 2017-12-13 04:04:29
categories: arXiv_AI
tags: arXiv_AI Segmentation Attention Reinforcement_Learning Relation
author: Jinyoung Choi, Beom-Jin Lee, Byoung-Tak Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Deep reinforcement learning (DRL) has shown incredible performance in learning various tasks to the human level. However, unlike human perception, current DRL models connect the entire low-level sensory input to the state-action values rather than exploiting the relationship between and among entities that constitute the sensory input. Because of this difference, DRL needs vast amount of experience samples to learn. In this paper, we propose a Multi-focus Attention Network (MANet) which mimics human ability to spatially abstract the low-level sensory input into multiple entities and attend to them simultaneously. The proposed method first divides the low-level input into several segments which we refer to as partial states. After this segmentation, parallel attention layers attend to the partial states relevant to solving the task. Our model estimates state-action values using these attended partial states. In our experiments, MANet attains highest scores with significantly less experience samples. Additionally, the model shows higher performance compared to the Deep Q-network and the single attention model as benchmarks. Furthermore, we extend our model to attentive communication model for performing multi-agent cooperative tasks. In multi-agent cooperative task experiments, our model shows 20% faster learning than existing state-of-the-art model.

##### Abstract (translated by Google)
深度强化学习（DRL）在向人类学习各种任务方面表现出令人难以置信的表现。然而，与人类感知不同的是，当前DRL模型将整个低级感官输入连接到状态行为值，而不是利用构成感官输入的实体之间的关系。由于这个差异，DRL需要大量的经验样本来学习。在本文中，我们提出了一个多重注意网络（MANET），它模仿人类将低级感官输入空间抽象为多个实体的能力，并同时注意到它们。所提出的方法首先将低级输入分成几个段，我们称之为部分状态。在这个分割之后，并行的关注层将关注与解决任务相关的部分状态。我们的模型使用这些参与的部分状态估计状态行为值。在我们的实验中，MANET获得了最高的分数，经验样本显着减少。此外，与Deep Q网络和单一关注模型相比，该模型显示出更高的性能。此外，我们将模型扩展到用于执行多智能体协作任务的专注通信模型。在多智能体协作任务实验中，我们的模型比现有的最先进的模型显示了20％的学习速度。

##### URL
[https://arxiv.org/abs/1712.04603](https://arxiv.org/abs/1712.04603)

##### PDF
[https://arxiv.org/pdf/1712.04603](https://arxiv.org/pdf/1712.04603)

