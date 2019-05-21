---
layout: post
title: "Reinforcement Learning without Ground-Truth State"
date: 2019-05-20 04:17:03
categories: arXiv_RO
tags: arXiv_RO Knowledge Reinforcement_Learning
author: Xingyu Lin, Harjatin Singh Baweja, David Held
mathjax: true
---

* content
{:toc}

##### Abstract
To perform robot manipulation tasks, a low dimension state of the environment typically needs to be estimated. However, designing a state estimator can sometimes be difficult, especially in environments with deformable objects. An alternative is to learn an end-to-end policy that maps directly from high dimensional sensor inputs to actions. However, if this policy is trained with reinforcement learning, then without a state estimator, it is hard to specify a reward function based on continuous and high dimensional observations. To meet this challenge, we propose a simple indicator reward function for goal-conditioned reinforcement learning: we only give a positive reward when the robot's observation exactly matches a target goal observation. We show that by utilizing the goal relabeling technique, we can learn with the indicator reward function even in continuous state spaces, in which we do not expect two observations to ever be identical. We propose two methods to further speed up convergence with indicator rewards: reward balancing and reward filtering. We show comparable performance between our method and an oracle which uses the ground-truth state for computing rewards, even though our method only operates on raw observations and does not have access to the ground-truth state. We demonstrate our method in complex tasks in continuous state spaces such as rope manipulation from RGB-D images, without knowledge of the ground truth state.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.07866](http://arxiv.org/abs/1905.07866)

##### PDF
[http://arxiv.org/pdf/1905.07866](http://arxiv.org/pdf/1905.07866)

