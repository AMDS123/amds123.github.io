---
layout: post
title: "Virtual-Taobao: Virtualizing Real-world Online Retail Environment for Reinforcement Learning"
date: 2018-05-25 06:39:31
categories: arXiv_AI
tags: arXiv_AI Adversarial GAN Reinforcement_Learning
author: Jing-Cheng Shi, Yang Yu, Qing Da, Shi-Yong Chen, An-Xiang Zeng
mathjax: true
---

* content
{:toc}

##### Abstract
Applying reinforcement learning in physical-world tasks is extremely challenging. It is commonly infeasible to sample a large number of trials, as required by current reinforcement learning methods, in a physical environment. This paper reports our project on using reinforcement learning for better commodity search in Taobao, one of the largest online retail platforms and meanwhile a physical environment with a high sampling cost. Instead of training reinforcement learning in Taobao directly, we present our approach: first we build Virtual Taobao, a simulator learned from historical customer behavior data through the proposed GAN-SD (GAN for Simulating Distributions) and MAIL (multi-agent adversarial imitation learning), and then we train policies in Virtual Taobao with no physical costs in which ANC (Action Norm Constraint) strategy is proposed to reduce over-fitting. In experiments, Virtual Taobao is trained from hundreds of millions of customers' records, and its properties are compared with the real environment. The results disclose that Virtual Taobao faithfully recovers important properties of the real environment. We also show that the policies trained in Virtual Taobao can have significantly superior online performance to the traditional supervised approaches. We hope our work could shed some light on reinforcement learning applications in complex physical environments.

##### Abstract (translated by Google)
在物理世界的任务中应用强化学习非常具有挑战性。根据目前强化学习方法的要求，在物理环境中抽样大量试验通常是不可行的。本文报道了我们在淘宝网上使用强化学习进行更好的商品搜索的项目，淘宝网是最大的在线零售平台之一，同时具有高采样成本的物理环境。我们不是直接在淘宝训练强化学习，而是提出我们的方法：首先，我们通过建议的GAN-SD（GAN for Simulating Distributions）和MAIL（多智能体仿制学习）建立虚拟淘宝，一个从历史客户行为数据中学习的模拟器， ，然后我们在虚拟淘宝中培训政策，没有物理成本，其中提出ANC（行动规范约束）策略来减少过度拟合。在实验中，虚拟淘宝通过数以亿计的客户记录进行培训，并将其属性与真实环境进行比较。结果显示虚拟淘宝忠实地恢复了真实环境的重要属性。我们还表明，在虚拟淘宝培训的政策可以有显着优越的在线表现，传统的监督方法。我们希望我们的工作能够在复杂的物理环境中强化学习应用。

##### URL
[http://arxiv.org/abs/1805.10000](http://arxiv.org/abs/1805.10000)

##### PDF
[http://arxiv.org/pdf/1805.10000](http://arxiv.org/pdf/1805.10000)

