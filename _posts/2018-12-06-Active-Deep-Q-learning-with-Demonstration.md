---
layout: post
title: "Active Deep Q-learning with Demonstration"
date: 2018-12-06 16:13:43
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Si-An Chen, Voot Tangkaratt, Hsuan-Tien Lin, Masashi Sugiyama
mathjax: true
---

* content
{:toc}

##### Abstract
Recent research has shown that although Reinforcement Learning (RL) can benefit from expert demonstration, it usually takes considerable efforts to obtain enough demonstration. The efforts prevent training decent RL agents with expert demonstration in practice. In this work, we propose Active Reinforcement Learning with Demonstration (ARLD), a new framework to streamline RL in terms of demonstration efforts by allowing the RL agent to query for demonstration actively during training. Under the framework, we propose Active Deep Q-Network, a novel query strategy which adapts to the dynamically-changing distributions during the RL training process by estimating the uncertainty of recent states. The expert demonstration data within Active DQN are then utilized by optimizing supervised max-margin loss in addition to temporal difference loss within usual DQN training. We propose two methods of estimating the uncertainty based on two state-of-the-art DQN models, namely the divergence of bootstrapped DQN and the variance of noisy DQN. The empirical results validate that both methods not only learn faster than other passive expert demonstration methods with the same amount of demonstration and but also reach super-expert level of performance across four different tasks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.02632](http://arxiv.org/abs/1812.02632)

##### PDF
[http://arxiv.org/pdf/1812.02632](http://arxiv.org/pdf/1812.02632)

