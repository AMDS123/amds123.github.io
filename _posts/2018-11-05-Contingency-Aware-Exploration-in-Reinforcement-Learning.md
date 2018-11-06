---
layout: post
title: "Contingency-Aware Exploration in Reinforcement Learning"
date: 2018-11-05 02:12:11
categories: arXiv_AI
tags: arXiv_AI Sparse Reinforcement_Learning
author: Jongwook Choi, Yijie Guo, Marcin Moczulski, Junhyuk Oh, Neal Wu, Mohammad Norouzi, Honglak Lee
mathjax: true
---

* content
{:toc}

##### Abstract
This paper investigates whether learning contingency-awareness and controllable aspects of an environment can lead to better exploration in reinforcement learning. To investigate this question, we consider an instantiation of this hypothesis evaluated on the Arcade Learning Element (ALE). In this study, we develop an attentive dynamics model (ADM) that discovers controllable elements of the observations, which are often associated with the location of the character in Atari games. The ADM is trained in a self-supervised fashion to predict the actions taken by the agent. The learned contingency information is used as a part of the state representation for exploration purposes. We demonstrate that combining A2C with count-based exploration using our representation achieves impressive results on a set of notoriously challenging Atari games due to sparse rewards. For example, we report a state-of-the-art score of &gt;6600 points on Montezuma's Revenge without using expert demonstrations, explicit high-level information (e.g., RAM states), or supervised data. Our experiments confirm that indeed contingency-awareness is an extremely powerful concept for tackling exploration problems in reinforcement learning and opens up interesting research questions for further investigations.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.01483](http://arxiv.org/abs/1811.01483)

##### PDF
[http://arxiv.org/pdf/1811.01483](http://arxiv.org/pdf/1811.01483)

