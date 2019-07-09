---
layout: post
title: "Self-supervised Learning of Distance Functions for Goal-Conditioned Reinforcement Learning"
date: 2019-07-05 19:00:14
categories: arXiv_AI
tags: arXiv_AI Knowledge Reinforcement_Learning
author: Srinivas Venkattaramanujam, Eric Crawford, Thang Doan, Doina Precup
mathjax: true
---

* content
{:toc}

##### Abstract
Goal-conditioned policies are used in order to break down complex reinforcement learning (RL) problems by using subgoals, which can be defined either in state space or in a latent feature space. This can increase the efficiency of learning by using a curriculum, and also enables simultaneous learning and generalization across goals. A crucial requirement of goal-conditioned policies is to be able to determine whether the goal has been achieved. Having a notion of distance to a goal is thus a crucial component of this approach. However, it is not straightforward to come up with an appropriate distance, and in some tasks, the goal space may not even be known a priori. In this work we learn a distance-to-goal estimate which is computed in terms of the number of actions that would need to be carried out in a self-supervised approach. Our method solves complex tasks without prior domain knowledge in the online setting in three different scenarios in the context of goal-conditioned policies a) the goal space is the same as the state space b) the goal space is given but an appropriate distance is unknown and c) the state space is accessible, but only a subset of the state space represents desired goals, and this subset is known a priori. We also propose a goal-generation mechanism as a secondary contribution.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.02998](http://arxiv.org/abs/1907.02998)

##### PDF
[http://arxiv.org/pdf/1907.02998](http://arxiv.org/pdf/1907.02998)

