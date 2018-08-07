---
layout: post
title: "Low-pass Recurrent Neural Networks - A memory architecture for longer-term correlation discovery"
date: 2018-05-13 21:35:08
categories: arXiv_CV
tags: arXiv_CV Reinforcement_Learning RNN Relation
author: Thomas Stepleton, Razvan Pascanu, Will Dabney, Siddhant M. Jayakumar, Hubert Soyer, Remi Munos
mathjax: true
---

* content
{:toc}

##### Abstract
Reinforcement learning (RL) agents performing complex tasks must be able to remember observations and actions across sizable time intervals. This is especially true during the initial learning stages, when exploratory behaviour can increase the delay between specific actions and their effects. Many new or popular approaches for learning these distant correlations employ backpropagation through time (BPTT), but this technique requires storing observation traces long enough to span the interval between cause and effect. Besides memory demands, learning dynamics like vanishing gradients and slow convergence due to infrequent weight updates can reduce BPTT's practicality; meanwhile, although online recurrent network learning is a developing topic, most approaches are not efficient enough to use as replacements. We propose a simple, effective memory strategy that can extend the window over which BPTT can learn without requiring longer traces. We explore this approach empirically on a few tasks and discuss its implications.

##### Abstract (translated by Google)
执行复杂任务的强化学习（RL）代理必须能够记住相当大的时间间隔内的观察和动作。在初始学习阶段尤其如此，当探索行为可以增加特定行动与其影响之间的延迟时。用于学习这些远距离相关性的许多新的或流行的方法采用反向传播（BPTT），但是该技术需要存储足够长的观察迹线以跨越原因和结果之间的间隔。除了记忆需求之外，学习动态如消失的渐变和由于不经常的重量更新导致的慢收敛可以降低BPTT的实用性;同时，虽然在线经常性网络学习是一个发展中的主题，但大多数方法都不足以用作替代品。我们提出了一种简单有效的内存策略，可以扩展BPTT可以学习的窗口，而无需更长的跟踪。我们根据一些任务凭经验探索这种方法并讨论其含义。

##### URL
[https://arxiv.org/abs/1805.04955](https://arxiv.org/abs/1805.04955)

##### PDF
[https://arxiv.org/pdf/1805.04955](https://arxiv.org/pdf/1805.04955)

