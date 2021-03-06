---
layout: post
title: "Deep Q-Learning with Q-Matrix Transfer Learning for Novel Fire Evacuation Environment"
date: 2019-05-23 14:15:51
categories: arXiv_AI
tags: arXiv_AI Attention Reinforcement_Learning Transfer_Learning
author: Jivitesh Sharma, Per-Arne Andersen, Ole-Chrisoffer Granmo, Morten Goodwin
mathjax: true
---

* content
{:toc}

##### Abstract
We focus on the important problem of emergency evacuation, which clearly could benefit from reinforcement learning that has been largely unaddressed. Emergency evacuation is a complex task which is difficult to solve with reinforcement learning, since an emergency situation is highly dynamic, with a lot of changing variables and complex constraints that makes it difficult to train on. In this paper, we propose the first fire evacuation environment to train reinforcement learning agents for evacuation planning. The environment is modelled as a graph capturing the building structure. It consists of realistic features like fire spread, uncertainty and bottlenecks. We have implemented the environment in the OpenAI gym format, to facilitate future research. We also propose a new reinforcement learning approach that entails pretraining the network weights of a DQN based agents to incorporate information on the shortest path to the exit. We achieved this by using tabular Q-learning to learn the shortest path on the building model's graph. This information is transferred to the network by deliberately overfitting it on the Q-matrix. Then, the pretrained DQN model is trained on the fire evacuation environment to generate the optimal evacuation path under time varying conditions. We perform comparisons of the proposed approach with state-of-the-art reinforcement learning algorithms like PPO, VPG, SARSA, A2C and ACKTR. The results show that our method is able to outperform state-of-the-art models by a huge margin including the original DQN based models. Finally, we test our model on a large and complex real building consisting of 91 rooms, with the possibility to move to any other room, hence giving 8281 actions. We use an attention based mechanism to deal with large action spaces. Our model achieves near optimal performance on the real world emergency environment.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.09673](http://arxiv.org/abs/1905.09673)

##### PDF
[http://arxiv.org/pdf/1905.09673](http://arxiv.org/pdf/1905.09673)

