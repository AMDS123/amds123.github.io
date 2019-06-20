---
layout: post
title: "QXplore: Q-learning Exploration by Maximizing Temporal Difference Error"
date: 2019-06-19 16:06:36
categories: arXiv_AI
tags: arXiv_AI Adversarial Sparse Reinforcement_Learning
author: Riley Simmons-Edler, Ben Eisner, Eric Mitchell, Sebastian Seung, Daniel Lee
mathjax: true
---

* content
{:toc}

##### Abstract
A major challenge in reinforcement learning for continuous state-action spaces is exploration, especially when reward landscapes are very sparse. Several recent methods provide an intrinsic motivation to explore by directly encouraging RL agents to seek novel states. A potential disadvantage of pure state novelty-seeking behavior is that unknown states are treated equally regardless of their potential for future reward. In this paper, we propose that the temporal difference error of predicting primary reward can serve as a secondary reward signal for exploration. This leads to novelty-seeking in the absence of primary reward, and at the same time accelerates exploration of reward-rich regions in sparse (but nonzero) reward landscapes compared to state novelty-seeking. This objective draws inspiration from dopaminergic pathways in the brain that influence animal behavior. We implement this idea with an adversarial method in which Q and Qx are the action-value functions for primary and secondary rewards, respectively. Secondary reward is given by the absolute value of the TD-error of Q. Training is off-policy, based on a replay buffer containing a mixture of trajectories induced by Q and Qx. We characterize performance on a suite of continuous control benchmark tasks against recent state of the art exploration methods and demonstrate comparable or better performance on all tasks, with much faster convergence for Q.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.08189](http://arxiv.org/abs/1906.08189)

##### PDF
[http://arxiv.org/pdf/1906.08189](http://arxiv.org/pdf/1906.08189)

