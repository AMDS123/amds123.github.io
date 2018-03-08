---
layout: post
title: "A Deeper Look at Experience Replay"
date: 2018-03-07 16:35:12
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Shangtong Zhang, Richard S. Sutton
mathjax: true
---

* content
{:toc}

##### Abstract
Recently experience replay is widely used in various deep reinforcement learning (RL) algorithms, however in this paper we showcase that it is not as good as people think. To be more specific, experience replay will significantly hurt the learning process if the size of replay buffer is not well tuned. Although experience replay is a necessary component in modern deep RL algorithms to stabilize the network, we should be aware that the idea of experience replay itself is not as good as people think. The size of the replay buffer is an important hyper-parameter, which can significantly influence the performance and has unfortunately been underestimated in the community for a long time. In this paper we did a systematic empirical study of experience replay under various function representations. We showcase that a large replay buffer can significantly hurt the performance. Moreover, we propose a simple O(1) method to remedy the negative influence of a large replay buffer. We showcase its utility in both simple grid world and challenging domains like Atari games. Moreover, we visualize how a large replay buffer hurts the learning process.

##### Abstract (translated by Google)
最近的经验回放广泛用于各种深度强化学习（RL）算法，然而在本文中，我们展示了它不如人们想象的那么好。更具体地说，如果重播缓冲区的大小没有很好地调整，经验重播将严重影响学习过程。虽然经验回放是现代深度RL算法稳定网络的必要组成部分，但我们应该意识到，体验回放本身并不像人们想象的那么好。重播缓冲区的大小是一个重要的超参数，它可以显着影响性能，并且在很长一段时间内不幸在社区中被低估。在本文中，我们对各种函数表示下的经验重放进行了系统的实证研究。我们展示了一个大的重播缓冲区可能会严重影响性能。此外，我们提出了一个简单的O（1）方法来弥补大型重播缓冲区的负面影响。我们在简单的网格世界和Atari游戏等具有挑战性的领域展示其实用性。此外，我们想象一个大的重播缓冲区如何伤害学习过程。

##### URL
[http://arxiv.org/abs/1712.01275](http://arxiv.org/abs/1712.01275)

##### PDF
[http://arxiv.org/pdf/1712.01275](http://arxiv.org/pdf/1712.01275)

