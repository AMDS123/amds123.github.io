---
layout: post
title: "Data-Efficient Hierarchical Reinforcement Learning"
date: 2018-05-21 21:33:44
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Ofir Nachum, Shane Gu, Honglak Lee, Sergey Levine
mathjax: true
---

* content
{:toc}

##### Abstract
Hierarchical reinforcement learning (HRL) is a promising approach to extend traditional reinforcement learning (RL) methods to solve more complex tasks. Yet, the majority of current HRL methods require careful task-specific design and on-policy training, making them difficult to apply in real-world scenarios. In this paper, we study how we can develop HRL algorithms that are general, in that they do not make onerous additional assumptions beyond standard RL algorithms, and efficient, in the sense that they can be used with modest numbers of interaction samples, making them suitable for real-world problems such as robotic control. For generality, we develop a scheme where lower-level controllers are supervised with goals that are learned and proposed automatically by the higher-level controllers. To address efficiency, we propose to use off-policy experience for both higher and lower-level training. This poses a considerable challenge, since changes to the lower-level behaviors change the action space for the higher-level policy, and we introduce an off-policy correction to remedy this challenge. This allows us to take advantage of recent advances in off-policy model-free RL to learn both higher- and lower-level policies using substantially fewer environment interactions than on-policy algorithms. We term the resulting HRL agent HIRO and find that it is generally applicable and highly sample-efficient. Our experiments show that HIRO can be used to learn highly complex behaviors for simulated robots, such as pushing objects and utilizing them to reach target locations, learning from only a few million samples, equivalent to a few days of real-time interaction. In comparisons with a number of prior HRL methods, we find that our approach substantially outperforms previous state-of-the-art techniques.

##### Abstract (translated by Google)
分层强化学习（HRL）是扩展传统强化学习（RL）方法以解决更复杂任务的有前途的方法。然而，目前大多数HRL方法需要仔细地进行特定任务的设计和策略培训，这使得它们难以应用于现实世界的情景中。在本文中，我们研究如何才能开发HRL算法是通用的，因为他们不作超出标准RL算法繁重的额外的假设，高效的，在这个意义上，他们可以与互动的样品适度电话号码一起使用，使他们适合现实世界的问题，如机器人控制。为了通用性，我们制定了一个方案，在这个方案中，较低级别的控制器受到上级控制器自动学习和提出的目标的监督。为了解决效率问题，我们建议在高层和低层培训中使用非政策性的经验。这是一个相当大的挑战，因为改变较低层次的行为改变了较高层次政策的行动空间，我们引入了一项非政策性修正来弥补这一挑战。这使得我们能够利用最近在无政策模型RL中取得的进步，使用比策略算法更少的环境交互来学习更高级别和更低级别的策略。我们将得到的HRL代理HIRO称为它，并发现它通常适用且具有高度的样本效率。我们的实验表明，HIRO可用于学习模拟机器人的高度复杂行为，例如推送物体并利用它们到达目标位置，从仅数百万个样本中学习，相当于几天的实时交互。与许多先前的HRL方法进行比较，我们发现我们的方法明显优于先前的最新技术。

##### URL
[https://arxiv.org/abs/1805.08296](https://arxiv.org/abs/1805.08296)

##### PDF
[https://arxiv.org/pdf/1805.08296](https://arxiv.org/pdf/1805.08296)

