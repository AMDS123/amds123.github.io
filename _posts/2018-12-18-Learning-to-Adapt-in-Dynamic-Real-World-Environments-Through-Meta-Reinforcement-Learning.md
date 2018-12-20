---
layout: post
title: "Learning to Adapt in Dynamic, Real-World Environments Through Meta-Reinforcement Learning"
date: 2018-12-18 21:55:30
categories: arXiv_RO
tags: arXiv_RO Pose_Estimation Reinforcement_Learning
author: Anusha Nagabandi, Ignasi Clavera, Simin Liu, Ronald S. Fearing, Pieter Abbeel, Sergey Levine, Chelsea Finn
mathjax: true
---

* content
{:toc}

##### Abstract
Although reinforcement learning methods can achieve impressive results in simulation, the real world presents two major challenges: generating samples is exceedingly expensive, and unexpected perturbations or unseen situations cause proficient but specialized policies to fail at test time. Given that it is impractical to train separate policies to accommodate all situations the agent may see in the real world, this work proposes to learn how to quickly and effectively adapt online to new tasks. To enable sample-efficient learning, we consider learning online adaptation in the context of model-based reinforcement learning. Our approach uses meta-learning to train a dynamics model prior such that, when combined with recent data, this prior can be rapidly adapted to the local context. Our experiments demonstrate online adaptation for continuous control tasks on both simulated and real-world agents. We first show simulated agents adapting their behavior online to novel terrains, crippled body parts, and highly-dynamic environments. We also illustrate the importance of incorporating online adaptation into autonomous agents that operate in the real world by applying our method to a real dynamic legged millirobot. We demonstrate the agent's learned ability to quickly adapt online to a missing leg, adjust to novel terrains and slopes, account for miscalibration or errors in pose estimation, and compensate for pulling payloads.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1803.11347](http://arxiv.org/abs/1803.11347)

##### PDF
[http://arxiv.org/pdf/1803.11347](http://arxiv.org/pdf/1803.11347)

