---
layout: post
title: "Transfer Learning for Prosthetics Using Imitation Learning"
date: 2019-01-15 11:35:26
categories: arXiv_AI
tags: arXiv_AI Knowledge Reinforcement_Learning Transfer_Learning Optimization
author: Montaser Mohammedalamen, Waleed D. Khamies, Benjamin Rosman
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, We Apply Reinforcement learning (RL) techniques to train a realistic biomechanical model to work with different people and on different walking environments. We benchmarking 3 RL algorithms: Deep Deterministic Policy Gradient (DDPG), Trust Region Policy Optimization (TRPO) and Proximal Policy Optimization (PPO) in OpenSim environment, Also we apply imitation learning to a prosthetics domain to reduce the training time needed to design customized prosthetics. We use DDPG algorithm to train an original expert agent. We then propose a modification to the Dataset Aggregation (DAgger) algorithm to reuse the expert knowledge and train a new target agent to replicate that behaviour in fewer than 5 iterations, compared to the 100 iterations taken by the expert agent which means reducing training time by 95%. Our modifications to the DAgger algorithm improve the balance between exploiting the expert policy and exploring the environment. We show empirically that these improve convergence time of the target agent, particularly when there is some degree of variation between expert and naive agent.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1901.04772](https://arxiv.org/abs/1901.04772)

##### PDF
[https://arxiv.org/pdf/1901.04772](https://arxiv.org/pdf/1901.04772)

