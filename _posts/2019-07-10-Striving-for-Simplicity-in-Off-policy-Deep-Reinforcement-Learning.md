---
layout: post
title: "Striving for Simplicity in Off-policy Deep Reinforcement Learning"
date: 2019-07-10 07:23:27
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Rishabh Agarwal, Dale Schuurmans, Mohammad Norouzi
mathjax: true
---

* content
{:toc}

##### Abstract
Reflecting on the advances of off-policy deep reinforcement learning (RL) algorithms since the development of DQN in 2013, it is important to ask: are the complexities of recent off-policy methods really necessary? In an attempt to isolate the contributions of various factors of variation in off-policy deep RL and to help design simpler algorithms, this paper investigates a set of related questions: First, can effective policies be learned given only access to logged offline experience? Second, how much of the benefits of recent distributional RL algorithms is attributed to improvements in exploration versus exploitation behavior? Third, can simpler off-policy RL algorithms outperform distributional RL without learning explicit distributions over returns? This paper uses a batch RL experimental setup on Atari 2600 games to investigate these questions. Unexpectedly, we find that batch RL algorithms trained solely on logged experiences of a DQN agent are able to significantly outperform online DQN. Our experiments suggest that the benefits of distributional RL mainly stem from better exploitation. We present a simple and novel variant of ensemble Q-learning called Random Ensemble Mixture (REM), which enforces optimal Bellman consistency on random convex combinations of the Q-heads of a multi-head Q-network. The batch REM agent trained offline on DQN data outperforms the batch QR-DQN and online C51 algorithms.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.04543](http://arxiv.org/abs/1907.04543)

##### PDF
[http://arxiv.org/pdf/1907.04543](http://arxiv.org/pdf/1907.04543)

