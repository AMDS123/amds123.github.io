---
layout: post
title: "Formulation of Deep Reinforcement Learning Architecture Toward Autonomous Driving for On-Ramp Merge"
date: 2019-02-02 02:04:20
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning RNN
author: Pin Wang, Ching-Yao Chan
mathjax: true
---

* content
{:toc}

##### Abstract
Multiple automakers have in development or in production automated driving systems (ADS) that offer freeway-pilot functions. This type of ADS is typically limited to restricted-access freeways only, that is, the transition from manual to automated modes takes place only after the ramp merging process is completed manually. One major challenge to extend the automation to ramp merging is that the automated vehicle needs to incorporate and optimize long-term objectives (e.g. successful and smooth merge) when near-term actions must be safely executed. Moreover, the merging process involves interactions with other vehicles whose behaviors are sometimes hard to predict but may influence the merging vehicle optimal actions. To tackle such a complicated control problem, we propose to apply Deep Reinforcement Learning (DRL) techniques for finding an optimal driving policy by maximizing the long-term reward in an interactive environment. Specifically, we apply a Long Short-Term Memory (LSTM) architecture to model the interactive environment, from which an internal state containing historical driving information is conveyed to a Deep Q-Network (DQN). The DQN is used to approximate the Q-function, which takes the internal state as input and generates Q-values as output for action selection. With this DRL architecture, the historical impact of interactive environment on the long-term reward can be captured and taken into account for deciding the optimal control policy. The proposed architecture has the potential to be extended and applied to other autonomous driving scenarios such as driving through a complex intersection or changing lanes under varying traffic flow conditions.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1709.02066](http://arxiv.org/abs/1709.02066)

##### PDF
[http://arxiv.org/pdf/1709.02066](http://arxiv.org/pdf/1709.02066)

