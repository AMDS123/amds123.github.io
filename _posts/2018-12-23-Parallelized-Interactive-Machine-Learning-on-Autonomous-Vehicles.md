---
layout: post
title: "Parallelized Interactive Machine Learning on Autonomous Vehicles"
date: 2018-12-23 14:57:28
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Xi Chen, Caylin Hickey
mathjax: true
---

* content
{:toc}

##### Abstract
Deep reinforcement learning (deep RL) has achieved superior performance in complex sequential tasks by learning directly from image input. A deep neural network is used as a function approximator and requires no specific state information. However, one drawback of using only images as input is that this approach requires a prohibitively large amount of training time and data for the model to learn the state feature representation and approach reasonable performance. This is not feasible in real-world applications, especially when the data are expansive and training phase could introduce disasters that affect human safety. In this work, we use a human demonstration approach to speed up training for learning features and use the resulting pre-trained model to replace the neural network in the deep RL Deep Q-Network (DQN), followed by human interaction to further refine the model. We empirically evaluate our approach by using only a human demonstration model and modified DQN with human demonstration model included in the Microsoft AirSim car simulator. Our results show that (1) pre-training with human demonstration in a supervised learning approach is better and much faster at discovering features than DQN alone, (2) initializing the DQN with a pre-trained model provides a significant improvement in training time and performance even with limited human demonstration, and (3) providing the ability for humans to supply suggestions during DQN training can speed up the network's convergence on an optimal policy, as well as allow it to learn more complex policies that are harder to discover by random exploration.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.09724](http://arxiv.org/abs/1812.09724)

##### PDF
[http://arxiv.org/pdf/1812.09724](http://arxiv.org/pdf/1812.09724)

