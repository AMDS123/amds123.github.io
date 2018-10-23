---
layout: post
title: "Graph Convolutional Reinforcement Learning for Multi-Agent Cooperation"
date: 2018-10-22 12:17:40
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning CNN Relation
author: Jiechuan Jiang, Chen Dun, Zongqing Lu
mathjax: true
---

* content
{:toc}

##### Abstract
Learning to cooperate is crucially important in multi-agent reinforcement learning. The key is to take the influence of other agents into consideration when performing distributed decision making. However, multi-agent environment is highly dynamic, which makes it hard to learn abstract representations of influences between agents by only low-order features that existing methods exploit. In this paper, we propose a graph convolutional model for multi-agent cooperation. The graph convolution architecture adapts to the dynamics of the underlying graph of the multi-agent environment, where the influence among agents is captured by their abstract relation representations. High-order features extracted by relation kernels of convolutional layers from gradually increased receptive fields are exploited to learn cooperative strategies. The gradient of an agent not only backpropagates to itself but also to other agents in its receptive fields to reinforce the learned cooperative strategies. Moreover, the relation representations are temporally regularized to make the cooperation more consistent. Empirically, we show that our model enables agents to develop more cooperative and sophisticated strategies than existing methods in jungle and battle games and routing in packet switching networks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.09202](http://arxiv.org/abs/1810.09202)

##### PDF
[http://arxiv.org/pdf/1810.09202](http://arxiv.org/pdf/1810.09202)

