---
layout: post
title: "Long-Range Indoor Navigation with PRM-RL"
date: 2019-02-25 17:20:06
categories: arXiv_AI
tags: arXiv_AI Face Reinforcement_Learning
author: Anthony Francis, Aleksandra Faust, Hao-Tien Lewis Chiang, Jasmine Hsu, J. Chase Kew, Marek Fiser, Tsang-Wei Edward Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Long-range indoor navigation requires guiding robots with noisy sensors and controls through cluttered environments along paths that span a variety of buildings. We achieve this with PRM-RL, a hierarchical robot navigation method in which reinforcement learning agents that map noisy sensors to robot controls learn to solve short-range obstacle avoidance tasks, and then sampling-based planners map where these agents can reliably navigate in simulation; these roadmaps and agents are then deployed on-robot, guiding the robot along the shortest path where the agents are likely to succeed. Here we use Probabilistic Roadmaps (PRMs) as the sampling-based planner and AutoRL as the reinforcement learning method in the indoor navigation context. We evaluate the method in simulation for kinematic differential drive and kinodynamic car-like robots in several environments, and on-robot for differential-drive robots at two physical sites. Our results show PRM-RL with AutoRL is more successful than several baselines, is robust to noise, and can guide robots over hundreds of meters in the face of noise and obstacles in both simulation and on-robot, including over 3.3 kilometers of physical robot navigation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.09458](http://arxiv.org/abs/1902.09458)

##### PDF
[http://arxiv.org/pdf/1902.09458](http://arxiv.org/pdf/1902.09458)

