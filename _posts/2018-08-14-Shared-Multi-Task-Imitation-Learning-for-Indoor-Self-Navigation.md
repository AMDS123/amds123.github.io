---
layout: post
title: "Shared Multi-Task Imitation Learning for Indoor Self-Navigation"
date: 2018-08-14 01:38:47
categories: arXiv_AI
tags: arXiv_AI
author: Junhong Xu, Qiwei Liu, Hanqing Guo, Aaron Kageza, Saeed AlQarni, Shaoen Wu
mathjax: true
---

* content
{:toc}

##### Abstract
Deep imitation learning enables robots to learn from expert demonstrations to perform tasks such as lane following or obstacle avoidance. However, in the traditional imitation learning framework, one model only learns one task, and thus it lacks of the capability to support a robot to perform various different navigation tasks with one model in indoor environments. This paper proposes a new framework, Shared Multi-headed Imitation Learning(SMIL), that allows a robot to perform multiple tasks with one model without switching among different models. We model each task as a sub-policy and design a multi-headed policy to learn the shared information among related tasks by summing up activations from all sub-policies. Compared to single or non-shared multi-headed policies, this framework is able to leverage correlated information among tasks to increase performance.We have implemented this framework using a robot based on NVIDIA TX2 and performed extensive experiments in indoor environments with different baseline solutions. The results demonstrate that SMIL has doubled the performance over nonshared multi-headed policy.

##### Abstract (translated by Google)
深度模仿学习使机器人能够从专家演示中学习，以执行诸如车道跟踪或避障等任务。然而，在传统的模仿学习框架中，一个模型仅学习一个任务，因此缺乏支持机器人在室内环境中用一个模型执行各种不同导航任务的能力。本文提出了一个新的框架，共享多头模仿学习（SMIL），它允许机器人用一个模型执行多个任务，而不需要在不同模型之间切换。我们将每项任务建模为子策略，并设计一个多头策略，通过总结所有子策略的激活来了解相关任务之间的共享信息。与单一或非共享多头策略相比，该框架能够利用任务之间的相关信息来提高性能。我们使用基于NVIDIA TX2的机器人实现了该框架，并在具有不同基线解决方案的室内环境中进行了大量实验。结果表明，与非共同多头政策相比，SMIL的表现翻了一番。

##### URL
[http://arxiv.org/abs/1808.04503](http://arxiv.org/abs/1808.04503)

##### PDF
[http://arxiv.org/pdf/1808.04503](http://arxiv.org/pdf/1808.04503)

