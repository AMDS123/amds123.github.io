---
layout: post
title: "Imitating Human Search Strategies for Assembly"
date: 2018-09-13 09:49:24
categories: arXiv_RO
tags: arXiv_RO
author: Dennis Ehlers, Markku Suomalainen, Jens Lundell, Ville Kyrki
mathjax: true
---

* content
{:toc}

##### Abstract
We present a Learning from Demonstration method for teaching robots to perform search strategies imitated from humans for scenarios where, for example, assembly tasks fail due to position uncertainty. The method utilizes human demonstrations to learn both a state invariant dynamics model and an exploration distribution that captures the search area covered by the demonstrator. We present two alternative algorithms for computing a search trajectory from the exploration distribution, one based on sampling and another based on deterministic ergodic control. We augment the search trajectory with forces learnt through the dynamics model to enable searching both in force and position domains. An impedance controller with superposed forces is used for reproducing the learnt strategy. We experimentally evaluate the method on a KUKA LWR4+ performing a 2D peg-in-hole and a 3D electricity socket tasks. Results show that the proposed method can with only few human demonstrations learn to complete the search task.

##### Abstract (translated by Google)
我们提出了一种学习示范方法，用于教授机器人以执行模仿人类的搜索策略，例如，由于位置不确定而导致装配任务失败。该方法利用人类演示来学习状态不变动力学模型和捕获示范者所覆盖的搜索区域的探索分布。我们提出了两种用于计算探索分布的搜索轨迹的替代算法，一种基于采样，另一种基于确定性遍历控制。我们利用通过动力学模型学习的力量来增强搜索轨迹，以便能够在力域和位置域中进行搜索。具有叠加力的阻抗控制器用于再现学习策略。我们通过实验评估KUKA LWR4 +上执行2D桩孔和3D电插座任务的方法。结果表明，所提出的方法只需很少的人工演示即可学会完成搜索任务。

##### URL
[http://arxiv.org/abs/1809.04860](http://arxiv.org/abs/1809.04860)

##### PDF
[http://arxiv.org/pdf/1809.04860](http://arxiv.org/pdf/1809.04860)

