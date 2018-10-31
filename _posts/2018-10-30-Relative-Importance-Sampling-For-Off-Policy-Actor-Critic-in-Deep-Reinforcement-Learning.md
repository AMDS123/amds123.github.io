---
layout: post
title: "Relative Importance Sampling For Off-Policy Actor-Critic in Deep Reinforcement Learning"
date: 2018-10-30 07:41:08
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Mahammad Humayoo, Xueqi Cheng
mathjax: true
---

* content
{:toc}

##### Abstract
Off-policy learning is more unstable compared to on-policy learning in reinforcement learning (RL). One reason for the instability of off-policy learning is a discrepancy between the target ($\pi$) and behavior (b) policy distributions. The discrepancy between $\pi$ and b distributions can be alleviated by employing a smooth variant of the importance sampling (IS), such as the relative importance sampling (RIS). RIS has parameter $\beta\in[0, 1]$ which controls smoothness. To cope with instability, we present the first relative importance sampling-off-policy actor-critic (RIS-Off-PAC) model-free algorithms in RL. In our method, the network yields a target policy (the actor), a value function (the critic) assessing the current policy ($\pi$), and behavior policy. We use action value generated from the behavior policy to train our algorithm rather than from the target policy. We also use deep neural networks to train both actor and critic. We evaluated our algorithm on a number of Open AI Gym benchmark problems and demonstrate better or comparable performance to several state-of-the-art RL baselines.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.12558](http://arxiv.org/abs/1810.12558)

##### PDF
[http://arxiv.org/pdf/1810.12558](http://arxiv.org/pdf/1810.12558)

