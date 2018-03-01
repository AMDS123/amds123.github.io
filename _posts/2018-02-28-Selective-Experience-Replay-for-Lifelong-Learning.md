---
layout: post
title: "Selective Experience Replay for Lifelong Learning"
date: 2018-02-28 06:02:31
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: David Isele, Akansel Cosgun
mathjax: true
---

* content
{:toc}

##### Abstract
Deep reinforcement learning has emerged as a powerful tool for a variety of learning tasks, however deep nets typically exhibit forgetting when learning multiple tasks in sequence. To mitigate forgetting, we propose an experience replay process that augments the standard FIFO buffer and selectively stores experiences in a long-term memory. We explore four strategies for selecting which experiences will be stored: favoring surprise, favoring reward, matching the global training distribution, and maximizing coverage of the state space. We show that distribution matching successfully prevents catastrophic forgetting, and is consistently the best approach on all domains tested. While distribution matching has better and more consistent performance, we identify one case in which coverage maximization is beneficial - when tasks that receive less trained are more important. Overall, our results show that selective experience replay, when suitable selection algorithms are employed, can prevent catastrophic forgetting.

##### Abstract (translated by Google)
深度强化学习已成为各种学习任务的强大工具，但深度网络通常会在按顺序学习多个任务时表现出遗忘。为了减轻遗忘，我们提出了一个体验重放过程，它扩展了标准的FIFO缓冲区，并有选择地将体验存储在长期记忆中。我们探索选择存储经验的四种策略：有利于惊喜，有利于奖励，匹配全球培训分布，以及最大化状态空间的覆盖范围。我们展示分配匹配成功地防止了灾难性遗忘，并始终是所有测试域的最佳方法。尽管分配匹配具有更好和更一致的性能，但我们确定了覆盖最大化有利的一种情况 - 受训较少的任务更重要。总的来说，我们的结果表明，选择性体验重播，当采用合适的选择算法时，可以防止灾难性遗忘。

##### URL
[http://arxiv.org/abs/1802.10269](http://arxiv.org/abs/1802.10269)

##### PDF
[http://arxiv.org/pdf/1802.10269](http://arxiv.org/pdf/1802.10269)

