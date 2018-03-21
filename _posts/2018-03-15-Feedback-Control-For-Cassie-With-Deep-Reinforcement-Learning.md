---
layout: post
title: "Feedback Control For Cassie With Deep Reinforcement Learning"
date: 2018-03-15 03:37:36
categories: arXiv_RO
tags: arXiv_RO Reinforcement_Learning
author: Zhaoming Xie, Glen Berseth, Patrick Clary, Jonathan Hurst, Michiel van de Panne
mathjax: true
---

* content
{:toc}

##### Abstract
Bipedal locomotion skills are challenging to develop. Control strategies often use local linearization of the dynamics in conjunction with reduced-order abstractions to yield tractable solutions. In these model-based control strategies, the controller is often not fully aware of many details, including torque limits, joint limits, and other non-linearities that are necessarily excluded from the control computations for simplicity. Deep reinforcement learning (DRL) offers a promising model-free approach for controlling bipedal locomotion which can more fully exploit the dynamics. However, current results in the machine learning literature are often based on ad-hoc simulation models that are not based on corresponding hardware. Thus it remains unclear how well DRL will succeed on realizable bipedal robots. In this paper, we demonstrate the effectiveness of DRL using a realistic model of Cassie, a bipedal robot. By formulating a feedback control problem as finding the optimal policy for a Markov Decision Process, we are able to learn robust walking controllers that imitate a reference motion with DRL. Controllers for different walking speeds are learned by imitating simple time-scaled versions of the original reference motion. Controller robustness is demonstrated through several challenging tests, including sensory delay, walking blindly on irregular terrain and unexpected pushes at the pelvis. We also show we can interpolate between individual policies and that robustness can be improved with an interpolated policy.

##### Abstract (translated by Google)
双足步行运动技能的发展具有挑战性。控制策略通常将动态的局部线性化与降阶抽象相结合以产生易处理的解决方案。在这些基于模型的控制策略中，控制器通常不会完全意识到许多细节，包括扭矩限制，接点限制以及为简单起见必须从控制计算中排除的其他非线性。深度强化学习（DRL）为控制双足机动提供了一种很有前途的无模型方法，可以更充分地利用动力学。然而，机器学习文献中的当前结果通常基于不基于相应硬件的特设仿真模型。因此目前还不清楚DRL在可实现的双足机器人方面的成功程度如何。在本文中，我们用一个双足机器人Cassie的真实模型来证明DRL的有效性。通过将反馈控制问题制定为寻找马尔科夫决策过程的最优策略，我们能够学习使用DRL模拟参考运动的稳健步行控制器。通过模拟原始参考运动的简单时标版本可以学习不同步行速度的控制器。通过几项具有挑战性的测试来证明控制器的稳健性，包括感官延迟，在不规则地形上盲目行走以及在骨盆处意外推动。我们还显示我们可以在各个政策之间进行插值，并且可以通过插值策略改进健壮性。

##### URL
[https://arxiv.org/abs/1803.05580](https://arxiv.org/abs/1803.05580)

##### PDF
[https://arxiv.org/pdf/1803.05580](https://arxiv.org/pdf/1803.05580)

