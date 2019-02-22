---
layout: post
title: "Curiosity-Driven Experience Prioritization via Density Estimation"
date: 2019-02-20 12:31:23
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Rui Zhao, Volker Tresp
mathjax: true
---

* content
{:toc}

##### Abstract
In Reinforcement Learning (RL), an agent explores the environment and collects trajectories into the memory buffer for later learning. However, the collected trajectories can easily be imbalanced with respect to the achieved goal states. The problem of learning from imbalanced data is a well-known problem in supervised learning, but has not yet been thoroughly researched in RL. To address this problem, we propose a novel Curiosity-Driven Prioritization (CDP) framework to encourage the agent to over-sample those trajectories that have rare achieved goal states. The CDP framework mimics the human learning process and focuses more on relatively uncommon events. We evaluate our methods using the robotic environment provided by OpenAI Gym. The environment contains six robot manipulation tasks. In our experiments, we combined CDP with Deep Deterministic Policy Gradient (DDPG) with or without Hindsight Experience Replay (HER). The experimental results show that CDP improves both performance and sample-efficiency of reinforcement learning agents, compared to state-of-the-art methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.08039](http://arxiv.org/abs/1902.08039)

##### PDF
[http://arxiv.org/pdf/1902.08039](http://arxiv.org/pdf/1902.08039)

