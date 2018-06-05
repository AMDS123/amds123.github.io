---
layout: post
title: "Integrating Episodic Memory into a Reinforcement Learning Agent using Reservoir Sampling"
date: 2018-06-01 20:52:31
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Deep_Learning
author: Kenny J. Young, Richard S. Sutton, Shuo Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Episodic memory is a psychology term which refers to the ability to recall specific events from the past. We suggest one advantage of this particular type of memory is the ability to easily assign credit to a specific state when remembered information is found to be useful. Inspired by this idea, and the increasing popularity of external memory mechanisms to handle long-term dependencies in deep learning systems, we propose a novel algorithm which uses a reservoir sampling procedure to maintain an external memory consisting of a fixed number of past states. The algorithm allows a deep reinforcement learning agent to learn online to preferentially remember those states which are found to be useful to recall later on. Critically this method allows for efficient online computation of gradient estimates with respect to the write process of the external memory. Thus unlike most prior mechanisms for external memory it is feasible to use in an online reinforcement learning setting.

##### Abstract (translated by Google)
情景记忆是一种心理学术语，指的是回忆过去特定事件的能力。我们建议这种特殊类型的记忆的一个优点是，当记忆的信息被发现有用时，能够轻松地将信用分配给特定的状态。受这个想法的启发，以及外部存储器机制在深度学习系统中处理长期依赖性的日益普及，我们提出了一种新颖的算法，该算法使用油藏采样过程来维护由固定数量的过去状态组成的外部存储器。该算法允许深度强化学习代理在线学习，以优先记住那些后来发现有用的状态。重要的是，这种方法可以有效地在线计算与外部存储器的写入过程相关的梯度估计值。因此，与大多数以前的外部存储器机制不同，使用在线强化学习设置是可行的。

##### URL
[http://arxiv.org/abs/1806.00540](http://arxiv.org/abs/1806.00540)

##### PDF
[http://arxiv.org/pdf/1806.00540](http://arxiv.org/pdf/1806.00540)

