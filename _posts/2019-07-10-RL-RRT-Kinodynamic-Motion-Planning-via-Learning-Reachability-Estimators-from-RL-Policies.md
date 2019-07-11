---
layout: post
title: "RL-RRT: Kinodynamic Motion Planning via Learning Reachability Estimators from RL Policies"
date: 2019-07-10 15:36:03
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Inference
author: Hao-Tien Lewis Chiang, Jasmine Hsu, Marek Fiser, Lydia Tapia, Aleksandra Faust
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses two challenges facing sampling-based kinodynamic motion planning: a way to identify good candidate states for local transitions and the subsequent computationally intractable steering between these candidate states. Through the combination of sampling-based planning, a Rapidly Exploring Randomized Tree (RRT) and an efficient kinodynamic motion planner through machine learning, we propose an efficient solution to long-range planning for kinodynamic motion planning. First, we use deep reinforcement learning to learn an obstacle-avoiding policy that maps a robot's sensor observations to actions, which is used as a local planner during planning and as a controller during execution. Second, we train a reachability estimator in a supervised manner, which predicts the RL policy's time to reach a state in the presence of obstacles. Lastly, we introduce RL-RRT that uses the RL policy as a local planner, and the reachability estimator as the distance function to bias tree-growth towards promising regions. We evaluate our method on three kinodynamic systems, including physical robot experiments. Results across all three robots tested indicate that RL-RRT outperforms state of the art kinodynamic planners in efficiency, and also provides a shorter path finish time than a steering function free method. The learned local planner policy and accompanying reachability estimator demonstrate transferability to the previously unseen experimental environments, making RL-RRT fast because the expensive computations are replaced with simple neural network inference.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.04799](http://arxiv.org/abs/1907.04799)

##### PDF
[http://arxiv.org/pdf/1907.04799](http://arxiv.org/pdf/1907.04799)

