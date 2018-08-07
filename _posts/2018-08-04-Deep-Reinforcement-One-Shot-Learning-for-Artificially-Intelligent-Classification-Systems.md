---
layout: post
title: "Deep Reinforcement One-Shot Learning for Artificially Intelligent Classification Systems"
date: 2018-08-04 20:13:35
categories: arXiv_AI
tags: arXiv_AI GAN Classification Detection
author: Anton Puzanov, Kobi Cohen
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years there has been a sharp rise in networking applications, in which significant events need to be classified but only a few training instances are available. These are known as cases of one-shot learning. Examples include analyzing network traffic under zero-day attacks, and computer vision tasks by sensor networks deployed in the field. To handle this challenging task, organizations often use human analysts to classify events under high uncertainty. Existing algorithms use a threshold-based mechanism to decide whether to classify an object automatically or send it to an analyst for deeper inspection. However, this approach leads to a significant waste of resources since it does not take the practical temporal constraints of system resources into account. Our contribution is threefold. First, we develop a novel Deep Reinforcement One-shot Learning (DeROL) framework to address this challenge. The basic idea of the DeROL algorithm is to train a deep-Q network to obtain a policy which is oblivious to the unseen classes in the testing data. Then, in real-time, DeROL maps the current state of the one-shot learning process to operational actions based on the trained deep-Q network, to maximize the objective function. Second, we develop the first open-source software for practical artificially intelligent one-shot classification systems with limited resources for the benefit of researchers in related fields. Third, we present an extensive experimental study using the OMNIGLOT dataset for computer vision tasks and the UNSW-NB15 dataset for intrusion detection tasks that demonstrates the versatility and efficiency of the DeROL framework.

##### Abstract (translated by Google)
近年来，网络应用程序急剧增加，其中需要对重要事件进行分类，但只有少数培训实例可用。这些被称为一次性学习的案例。示例包括分析零日攻击下的网络流量，以及现场部署的传感器网络的计算机视觉任务。为了应对这一具有挑战性的任务，组织通常使用人工分析师对高度不确定性下的事件进现有算法使用基于阈值的机制来决定是自动对对象进行分类还是将其发送给分析人员以进行更深入的检查。然而，这种方法导致资源的大量浪费，因为它没有考虑系统资源的实际时间限制。我们的贡献是三倍的。首先，我们开发了一种新的深度强化一次性学习（DeROL）框架来应对这一挑战。 DeROL算法的基本思想是训练深Q网络以获得对测试数据中看不见的类无关的策略。然后，DeROL实时地将一次性学习过程的当前状态映射到基于训练的深Q网络的操作动作，以最大化目标函数。其次，我们开发了第一个开源软件，用于实用的人工智能一次性分类系统，资源有限，为相关领域的研究人员带来益处。第三，我们使用用于计算机视觉任务的OMNIGLOT数据集和用于入侵检测任务的UNSW-NB15数据集进行了广泛的实验研究，该数据集展示了DeROL框架的多功能性和效率。

##### URL
[https://arxiv.org/abs/1808.01527](https://arxiv.org/abs/1808.01527)

##### PDF
[https://arxiv.org/pdf/1808.01527](https://arxiv.org/pdf/1808.01527)

