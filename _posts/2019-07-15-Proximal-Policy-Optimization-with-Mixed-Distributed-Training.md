---
layout: post
title: "Proximal Policy Optimization with Mixed Distributed Training"
date: 2019-07-15 12:56:38
categories: arXiv_AI
tags: arXiv_AI Sparse Reinforcement_Learning Optimization
author: Zhenyu Zhang, Xiangfeng Luo, Shaorong Xie, Jianshu Wang, Wei Wang, Yang Li
mathjax: true
---

* content
{:toc}

##### Abstract
Instability and slowness are two main problems in deep reinforcement learning. Even if proximal policy optimization is the state of the art, it still suffers from these two problems. We introduce an improved algorithm based on proximal policy optimization (PPO), mixed distributed proximal policy optimization (MDPPO), and show that it can accelerate and stabilize the training process. In our algorithm, multiple different policies train simultaneously and each of them controls several identical agents that interact with environments. Actions are sampled by each policy separately as usual but the trajectories for training process are collected from all agents, instead of only one policy. We find that if we choose some auxiliary trajectories elaborately to train policies, the algorithm will be more stable and quicker to converge especially in the environments with sparse rewards.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.06479](http://arxiv.org/abs/1907.06479)

##### PDF
[http://arxiv.org/pdf/1907.06479](http://arxiv.org/pdf/1907.06479)

