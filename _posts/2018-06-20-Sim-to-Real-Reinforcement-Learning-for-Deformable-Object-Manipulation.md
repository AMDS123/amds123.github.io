---
layout: post
title: "Sim-to-Real Reinforcement Learning for Deformable Object Manipulation"
date: 2018-06-20 17:22:12
categories: arXiv_AI
tags: arXiv_AI Face Reinforcement_Learning
author: Jan Matas, Stephen James, Andrew J. Davison
mathjax: true
---

* content
{:toc}

##### Abstract
We have seen much recent progress in rigid object manipulation, but interaction with deformable objects has notably lagged behind. Due to the large configuration space of deformable objects, solutions using traditional modelling approaches require significant engineering work. Perhaps then, bypassing the need for explicit modelling and instead learning the control in an end-to-end manner serves as a better approach? Despite the growing interest in the use of end-to-end robot learning approaches, only a small amount of work has focused on their applicability to deformable object manipulation. Moreover, due to the large amount of data needed to learn these end-to-end solutions, an emerging trend is to learn to control policies in simulation and then transfer them over to the real world. To-date, no work has explored whether it is possible to learn and transfer deformable object policies. We believe that if sim-to-real methods are the way forward, then it should be possible to learn to interact with a wide variety of objects, and not just rigid objects. In this work, we use a combination of state-of-the-art deep reinforcement learning algorithms to solve the problem of manipulating deformable objects (specifically cloth). We evaluate our approach on three tasks --- folding a towel up to a mark, folding a face towel diagonally, and draping a piece of cloth over a hanger. Our agents are fully trained in simulation with domain randomisation, and then successfully deployed in the real world without having seen any real deformable objects.

##### Abstract (translated by Google)
我们已经看到了刚体对象操作方面的最新进展，但与可变形对象的交互明显滞后。由于可变形物体的配置空间较大，使用传统建模方法的解决方案需要进行大量的工程工作。也许那么，绕过对显式建模的需求，而是以端到端的方式学习控制是一种更好的方法？尽管对端到端机器人学习方法的使用越来越感兴趣，但只有少量的工作集中在它们对可变形对象操纵的适用性上。此外，由于学习这些端到端解决方案所需的大量数据，一个新兴的趋势是学会在模拟中控制策略，然后将它们转移到现实世界。迄今为止，还没有工作探索是否有可能学习和传输可变形的对象策略。我们相信，如果sim-to-real方法是前进的方向，那么应该有可能学习与各种各样的对象进行交互，而不仅仅是刚性对象。在这项工作中，我们使用最先进的深度强化学习算法的组合来解决操纵可变形物体（特别是布料）的问题。我们通过三项任务来评估我们的方法 - 将毛巾折叠至标记，对角折叠面巾，并将衣服悬挂在衣架上。我们的代理完全接受领域随机化模拟训练，然后成功部署在现实世界中，而没有看到任何真正可变形的对象。

##### URL
[http://arxiv.org/abs/1806.07851](http://arxiv.org/abs/1806.07851)

##### PDF
[http://arxiv.org/pdf/1806.07851](http://arxiv.org/pdf/1806.07851)

