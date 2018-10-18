---
layout: post
title: "Integrating kinematics and environment context into deep inverse reinforcement learning for predicting off-road vehicle trajectories"
date: 2018-10-16 18:40:34
categories: arXiv_AI
tags: arXiv_AI Tracking Reinforcement_Learning Prediction
author: Yanfu Zhang, Wenshan Wang, Rogerio Bonatti, Daniel Maturana, Sebastian Scherer
mathjax: true
---

* content
{:toc}

##### Abstract
Predicting the motion of a mobile agent from a third-person perspective is an important component for many robotics applications, such as autonomous navigation and tracking. With accurate motion prediction of other agents, robots can plan for more intelligent behaviors to achieve specified objectives, instead of acting in a purely reactive way. Previous work addresses motion prediction by either only filtering kinematics, or using hand-designed and learned representations of the environment. Instead of separating kinematic and environmental context, we propose a novel approach to integrate both into an inverse reinforcement learning (IRL) framework for trajectory prediction. Instead of exponentially increasing the state-space complexity with kinematics, we propose a two-stage neural network architecture that considers motion and environment together to recover the reward function. The first-stage network learns feature representations of the environment using low-level LiDAR statistics and the second-stage network combines those learned features with kinematics data. We collected over 30 km of off-road driving data and validated experimentally that our method can effectively extract useful environmental and kinematic features. We generate accurate predictions of the distribution of future trajectories of the vehicle, encoding complex behaviors such as multi-modal distributions at road intersections, and even show different predictions at the same intersection depending on the vehicle's speed.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.07225](http://arxiv.org/abs/1810.07225)

##### PDF
[http://arxiv.org/pdf/1810.07225](http://arxiv.org/pdf/1810.07225)

