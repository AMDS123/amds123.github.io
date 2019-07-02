---
layout: post
title: "On mechanisms for transfer using landmark value functions in multi-task lifelong reinforcement learning"
date: 2019-07-01 15:56:24
categories: arXiv_AI
tags: arXiv_AI Face Reinforcement_Learning Transfer_Learning
author: Nick Denis
mathjax: true
---

* content
{:toc}

##### Abstract
Transfer learning across different reinforcement learning (RL) tasks is becoming an increasingly valuable area of research. We consider a goal-based multi-task RL framework and mechanisms by which previously solved tasks can reduce sample complexity and regret when the agent is faced with a new task. Specifically, we introduce two metrics on the state space that encode notions of traversibility of the state space for an agent. Using these metrics a topological covering is constructed by way of a set of landmark states in a fully self-supervised manner. We show that these landmark coverings confer theoretical advantages for transfer learning within the goal-based multi-task RL setting. Specifically, we demonstrate three mechanisms by which landmark coverings can be used for successful transfer learning. First, we extend the Landmark Options Via Reflection (LOVR) framework to this new topological covering; second, we use the landmark-centric value functions themselves as features and define a greedy zombie policy that achieves near oracle performance on a sequence of zero-shot transfer tasks; finally, motivated by the second transfer mechanism, we introduce a learned reward function that provides a more dense reward signal for goal-based RL. Our novel topological landmark covering confers beneficial theoretical results, bounding the Q values at each state-action pair. In doing so, we introduce a mechanism that performs action-pruning at infeasible actions which cannot possibly be part of an optimal policy for the current goal.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.00884](http://arxiv.org/abs/1907.00884)

##### PDF
[http://arxiv.org/pdf/1907.00884](http://arxiv.org/pdf/1907.00884)

