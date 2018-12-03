---
layout: post
title: "PEARL: PrEference Appraisal Reinforcement Learning for Motion Planning"
date: 2018-11-30 07:35:41
categories: arXiv_RO
tags: arXiv_RO Reinforcement_Learning
author: Aleksandra Faust, Hao-Tien Lewis Chiang, Lydia Tapia
mathjax: true
---

* content
{:toc}

##### Abstract
Robot motion planning often requires finding trajectories that balance different user intents, or preferences. One of these preferences is usually arrival at the goal, while another might be obstacle avoidance. Here, we formalize these, and similar, tasks as preference balancing tasks (PBTs) on acceleration controlled robots, and propose a motion planning solution, PrEference Appraisal Reinforcement Learning (PEARL). PEARL uses reinforcement learning on a restricted training domain, combined with features engineered from user-given intents. PEARL's planner then generates trajectories in expanded domains for more complex problems. We present an adaptation for rejection of stochastic disturbances and offer in-depth analysis, including task completion conditions and behavior analysis when the conditions do not hold. PEARL is evaluated on five problems, two multi-agent obstacle avoidance tasks and three that stochastically disturb the system at run-time: 1) a multi-agent pursuit problem with 1000 pursuers, 2) robot navigation through 900 moving obstacles, which is is trained with in an environment with only 4 static obstacles, 3) aerial cargo delivery, 4) two robot rendezvous, and 5) flying inverted pendulum. Lastly, we evaluate the method on a physical quadrotor UAV robot with a suspended load influenced by a stochastic disturbance. The video, https://youtu.be/ZkFt1uY6vlw contains the experiments and visualization of the simulations.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.12651](http://arxiv.org/abs/1811.12651)

##### PDF
[http://arxiv.org/pdf/1811.12651](http://arxiv.org/pdf/1811.12651)

