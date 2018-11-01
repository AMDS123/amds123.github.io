---
layout: post
title: "Differentiable MPC for End-to-end Planning and Control"
date: 2018-10-31 16:46:38
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Brandon Amos, Ivan Dario Jimenez Rodriguez, Jacob Sacks, Byron Boots, J. Zico Kolter
mathjax: true
---

* content
{:toc}

##### Abstract
We present foundations for using Model Predictive Control (MPC) as a differentiable policy class for reinforcement learning in continuous state and action spaces. This provides one way of leveraging and combining the advantages of model-free and model-based approaches. Specifically, we differentiate through MPC by using the KKT conditions of the convex approximation at a fixed point of the controller. Using this strategy, we are able to learn the cost and dynamics of a controller via end-to-end learning. Our experiments focus on imitation learning in the pendulum and cartpole domains, where we learn the cost and dynamics terms of an MPC policy class. We show that our MPC policies are significantly more data-efficient than a generic neural network and that our method is superior to traditional system identification in a setting where the expert is unrealizable.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.13400](http://arxiv.org/abs/1810.13400)

##### PDF
[http://arxiv.org/pdf/1810.13400](http://arxiv.org/pdf/1810.13400)

