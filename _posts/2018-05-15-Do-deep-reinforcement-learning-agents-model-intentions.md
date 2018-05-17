---
layout: post
title: "Do deep reinforcement learning agents model intentions?"
date: 2018-05-15 20:15:05
categories: arXiv_AI
tags: arXiv_AI Knowledge Reinforcement_Learning
author: Tambet Matiisen, Aqeel Labash, Daniel Majoral, Jaan Aru, Raul Vicente
mathjax: true
---

* content
{:toc}

##### Abstract
Inferring other agents' mental states such as their knowledge, beliefs and intentions is thought to be essential for effective interactions with other agents. Recently, multiagent systems trained via deep reinforcement learning have been shown to succeed in solving different tasks, but it remains unclear how each agent modeled or represented other agents in their environment. In this work we test whether deep reinforcement learning agents explicitly represent other agents' intentions (their specific aims or goals) during a task in which the agents had to coordinate the covering of different spots in a 2D environment. In particular, we tracked over time the performance of a linear decoder trained to predict the final goal of all agents from the hidden state of each agent's neural network controller. We observed that the hidden layers of agents represented explicit information about other agents' goals, i.e. the target landmark they ended up covering. We also performed a series of experiments, in which some agents were replaced by others with fixed goals, to test the level of generalization of the trained agents. We noticed that during the training phase the agents developed a differential preference for each goal, which hindered generalization. To alleviate the above problem, we propose simple changes to the MADDPG training algorithm which leads to better generalization against unseen agents. We believe that training protocols promoting more active intention reading mechanisms, e.g. by preventing simple symmetry-breaking solutions, is a promising direction towards achieving a more robust generalization in different cooperative and competitive tasks.

##### Abstract (translated by Google)
推断其他行为人的心理状态，如他们的知识，信仰和意图被认为是与其他行为人有效互动所必不可少的。最近，通过深度强化学习训练的多代理系统已被证明能够成功地解决不同的任务，但仍不清楚每个代理人如何在其环境中建模或表示其他代理人。在这项工作中，我们测试深度强化学习代理是否在代理必须协调2D环境中不同点的覆盖的任务中明确表示其他代理的意图（他们的具体目标或目标）。特别是，随着时间的推移，我们追踪了一个线性解码器的性能，该线性解码器被训练用来从每个代理的神经网络控制器的隐藏状态中预测所有代理的最终目标。我们观察到，隐藏的代理层代表了关于其他代理人目标的明确信息，即他们最终覆盖的目标地标。我们还进行了一系列实验，其中一些代理被具有固定目标的代理所取代，以测试受训代理的泛化水平。我们注意到，在训练阶段，代理人为每个目标制定了不同的偏好，这阻碍了泛化。为了缓解上述问题，我们对MADDPG训练算法提出了简单的改变，从而导致更好地推广未知代理。我们相信培训协议会促进更积极的意向阅读机制，例如通过防止简单的对称性破解解决方案，是在不同的合作和竞争任务中实现更强大的泛化的有前途的方向。

##### URL
[http://arxiv.org/abs/1805.06020](http://arxiv.org/abs/1805.06020)

##### PDF
[http://arxiv.org/pdf/1805.06020](http://arxiv.org/pdf/1805.06020)

