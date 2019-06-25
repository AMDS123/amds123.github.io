---
layout: post
title: "A Study of State Aliasing in Structured Prediction with RNNs"
date: 2019-06-21 20:16:52
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning RNN Prediction Recommendation
author: Layla El Asri, Adam Trischler
mathjax: true
---

* content
{:toc}

##### Abstract
End-to-end reinforcement learning agents learn a state representation and a policy at the same time. Recurrent neural networks (RNNs) have been trained successfully as reinforcement learning agents in settings like dialogue that require structured prediction. In this paper, we investigate the representations learned by RNN-based agents when trained with both policy gradient and value-based methods. We show through extensive experiments and analysis that, when trained with policy gradient, recurrent neural networks often fail to learn a state representation that leads to an optimal policy in settings where the same action should be taken at different states. To explain this failure, we highlight the problem of state aliasing, which entails conflating two or more distinct states in the representation space. We demonstrate that state aliasing occurs when several states share the same optimal action and the agent is trained via policy gradient. We characterize this phenomenon through experiments on a simple maze setting and a more complex text-based game, and make recommendations for training RNNs with reinforcement learning.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.09310](http://arxiv.org/abs/1906.09310)

##### PDF
[http://arxiv.org/pdf/1906.09310](http://arxiv.org/pdf/1906.09310)

