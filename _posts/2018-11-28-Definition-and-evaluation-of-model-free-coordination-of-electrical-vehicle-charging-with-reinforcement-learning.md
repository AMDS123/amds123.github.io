---
layout: post
title: "Definition and evaluation of model-free coordination of electrical vehicle charging with reinforcement learning"
date: 2018-11-28 19:00:36
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Nasrin Sadeghianpourhamami, Johannes Deleu, Chris Develder
mathjax: true
---

* content
{:toc}

##### Abstract
Initial DR studies mainly adopt model predictive control and thus require accurate models of the control problem (e.g., a customer behavior model), which are to a large extent uncertain for the EV scenario. Hence, model-free approaches, especially based on reinforcement learning (RL) are an attractive alternative. In this paper, we propose a new Markov decision process (MDP) formulation in the RL framework, to jointly coordinate a set of EV charging stations. State-of-the-art algorithms either focus on a single EV, or perform the control of an aggregate of EVs in multiple steps (e.g., aggregate load decisions in one step, then a step translating the aggregate decision to individual connected EVs). On the contrary, we propose an RL approach to jointly control the whole set of EVs at once. We contribute a new MDP formulation, with a scalable state representation that is independent of the number of EV charging stations. Further, we use a batch reinforcement learning algorithm, i.e., an instance of fitted Q-iteration, to learn the optimal charging policy. We analyze its performance using simulation experiments based on a real-world EV charging data. More specifically, we (i) explore the various settings in training the RL policy (e.g., duration of the period with training data), (ii) compare its performance to an oracle all-knowing benchmark (which provides an upper bound for performance, relying on information that is not available or at least imperfect in practice), (iii) analyze performance over time, over the course of a full year to evaluate possible performance fluctuations (e.g, across different seasons), and (iv) demonstrate the generalization capacity of a learned control policy to larger sets of charging stations.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1809.10679](http://arxiv.org/abs/1809.10679)

##### PDF
[http://arxiv.org/pdf/1809.10679](http://arxiv.org/pdf/1809.10679)

