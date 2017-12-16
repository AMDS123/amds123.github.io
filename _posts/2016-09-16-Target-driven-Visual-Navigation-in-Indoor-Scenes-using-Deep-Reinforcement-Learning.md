---
layout: post
title: "Target-driven Visual Navigation in Indoor Scenes using Deep Reinforcement Learning"
date: 2016-09-16 17:16:49
categories: arXiv_CV
tags: arXiv_CV Reinforcement_Learning
author: Yuke Zhu, Roozbeh Mottaghi, Eric Kolve, Joseph J. Lim, Abhinav Gupta, Li Fei-Fei, Ali Farhadi
mathjax: true
---

* content
{:toc}

##### Abstract
Two less addressed issues of deep reinforcement learning are (1) lack of generalization capability to new target goals, and (2) data inefficiency i.e., the model requires several (and often costly) episodes of trial and error to converge, which makes it impractical to be applied to real-world scenarios. In this paper, we address these two issues and apply our model to the task of target-driven visual navigation. To address the first issue, we propose an actor-critic model whose policy is a function of the goal as well as the current state, which allows to better generalize. To address the second issue, we propose AI2-THOR framework, which provides an environment with high-quality 3D scenes and physics engine. Our framework enables agents to take actions and interact with objects. Hence, we can collect a huge number of training samples efficiently. We show that our proposed method (1) converges faster than the state-of-the-art deep reinforcement learning methods, (2) generalizes across targets and across scenes, (3) generalizes to a real robot scenario with a small amount of fine-tuning (although the model is trained in simulation), (4) is end-to-end trainable and does not need feature engineering, feature matching between frames or 3D reconstruction of the environment. The supplementary video can be accessed at the following link: this https URL

##### Abstract (translated by Google)
两个较少的深层强化学习问题是：（1）缺乏对新的目标目标的泛化能力;（2）数据低效率，即模型需要几次（通常是昂贵的）试错的事件汇合，这使得它不切实际应用于真实世界的场景。在本文中，我们解决这两个问题，并将我们的模型应用于目标驱动的视觉导航任务。为了解决第一个问题，我们提出了一个行为者 - 评论者模型，其政策是目标的功能以及当前状态，从而可以更好地概括。为了解决第二个问题，我们提出了AI2-THOR框架，它提供了一个高质量的3D场景和物理引擎的环境。我们的框架使代理能够采取行动并与对象进行交互。因此，我们可以高效地收集大量的训练样本。我们表明，我们提出的方法（1）收敛速度比最先进的深度强化学习方法，（2）跨目标和跨场景，（3）推广到一个真正的机器人场景与少量的罚款（尽管该模型是在仿真中训练的），（4）是端到端可训练的，不需要特征工程，帧之间的特征匹配或环境的三维重建。补充视频可通过以下链接访问：https网址

##### URL
[https://arxiv.org/abs/1609.05143](https://arxiv.org/abs/1609.05143)

##### PDF
[https://arxiv.org/pdf/1609.05143](https://arxiv.org/pdf/1609.05143)

