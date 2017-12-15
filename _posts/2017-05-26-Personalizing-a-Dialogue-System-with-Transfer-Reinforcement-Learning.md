---
layout: post
title: "Personalizing a Dialogue System with Transfer Reinforcement Learning"
date: 2017-05-26 14:05:07
categories: arXiv_CL
tags: arXiv_CL Knowledge Reinforcement_Learning Transfer_Learning
author: Kaixiang Mo, Shuangyin Li, Yu Zhang, Jiajun Li, Qiang Yang
mathjax: true
---

* content
{:toc}

##### Abstract
It is difficult to train a personalized task-oriented dialogue system because the data collected from each individual is often insufficient. Personalized dialogue systems trained on a small dataset can overfit and make it difficult to adapt to different user needs. One way to solve this problem is to consider a collection of multiple users' data as a source domain and an individual user's data as a target domain, and to perform a transfer learning from the source to the target domain. By following this idea, we propose "PETAL"(PErsonalized Task-oriented diALogue), a transfer-learning framework based on POMDP to learn a personalized dialogue system. The system first learns common dialogue knowledge from the source domain and then adapts this knowledge to the target user. This framework can avoid the negative transfer problem by considering differences between source and target users. The policy in the personalized POMDP can learn to choose different actions appropriately for different users. Experimental results on a real-world coffee-shopping data and simulation data show that our personalized dialogue system can choose different optimal actions for different users, and thus effectively improve the dialogue quality under the personalized setting.

##### Abstract (translated by Google)
由于每个人收集的数据往往不够，所以很难培训个性化的任务型对话系统。在小数据集上训练的个性化对话系统可能会过度适应，并且难以适应不同的用户需求。解决这个问题的一种方法是将多个用户的数据集合作为源域，将单个用户的数据作为目标域，并且执行从源到目标域的转移学习。遵循这个思路，我们提出了基于POMDP的“PETAL”（面向任务的diALogue），这是一个基于POMDP的学习框架，用于学习个性化的对话系统。系统首先从源域学习常用对话知识，然后将这些知识应用到目标用户。这个框架可以通过考虑源和目标用户之间的差异来避免负面转移问题。个性化POMDP中的策略可以学习为不同的用户适当地选择不同的行为。实际的咖啡购物数据和仿真数据的实验结果表明，我们的个性化对话系统可以为不同的用户选择不同的最佳动作，从而有效地提高个性化设置下的对话质量。

##### URL
[https://arxiv.org/abs/1610.02891](https://arxiv.org/abs/1610.02891)

##### PDF
[https://arxiv.org/pdf/1610.02891](https://arxiv.org/pdf/1610.02891)

