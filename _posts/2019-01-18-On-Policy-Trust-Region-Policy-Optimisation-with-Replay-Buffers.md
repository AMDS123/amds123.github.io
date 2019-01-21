---
layout: post
title: "On-Policy Trust Region Policy Optimisation with Replay Buffers"
date: 2019-01-18 13:09:18
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Dmitry Kangin, Nicolas Pugeault
mathjax: true
---

* content
{:toc}

##### Abstract
Building upon the recent success of deep reinforcement learning methods, we investigate the possibility of on-policy reinforcement learning improvement by reusing the data from several consecutive policies. On-policy methods bring many benefits, such as ability to evaluate each resulting policy. However, they usually discard all the information about the policies which existed before. In this work, we propose adaptation of the replay buffer concept, borrowed from the off-policy learning setting, to create the method, combining advantages of on- and off-policy learning. To achieve this, the proposed algorithm generalises the $Q$-, value and advantage functions for data from multiple policies. The method uses trust region optimisation, while avoiding some of the common problems of the algorithms such as TRPO or ACKTR: it uses hyperparameters to replace the trust region selection heuristics, as well as the trainable covariance matrix instead of the fixed one. In many cases, the method not only improves the results comparing to the state-of-the-art trust region on-policy learning algorithms such as PPO, ACKTR and TRPO, but also with respect to their off-policy counterpart DDPG.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.06212](http://arxiv.org/abs/1901.06212)

##### PDF
[http://arxiv.org/pdf/1901.06212](http://arxiv.org/pdf/1901.06212)

