---
layout: post
title: "Negative Update Intervals in Deep Multi-Agent Reinforcement Learning"
date: 2019-05-07 09:34:03
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Gregory Palmer, Rahul Savani, Karl Tuyls
mathjax: true
---

* content
{:toc}

##### Abstract
In Multi-Agent Reinforcement Learning (MA-RL), independent cooperative learners must overcome a number of pathologies to learn optimal joint policies. Addressing one pathology often leaves approaches vulnerable towards others. For instance, hysteretic Q-learning addresses miscoordination while leaving agents vulnerable towards misleading stochastic rewards. Other methods, such as leniency, have proven more robust when dealing with multiple pathologies simultaneously. However, leniency has predominately been studied within the context of strategic form games (bimatrix games) and fully observable Markov games consisting of a small number of probabilistic state transitions. This raises the question of whether these findings scale to more complex domains. For this purpose we implement a temporally extend version of the Climb Game, within which agents must overcome multiple pathologies simultaneously, including relative overgeneralisation, stochasticity, the alter-exploration and moving target problems, while learning from a large observation space. We find that existing lenient and hysteretic approaches fail to consistently learn near optimal joint-policies in this environment. To address these pathologies we introduce Negative Update Intervals-DDQN (NUI-DDQN), a Deep MA-RL algorithm which discards episodes yielding cumulative rewards outside the range of expanding intervals. NUI-DDQN consistently gravitates towards optimal joint-policies in our environment, overcoming the outlined pathologies.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1809.05096](http://arxiv.org/abs/1809.05096)

##### PDF
[http://arxiv.org/pdf/1809.05096](http://arxiv.org/pdf/1809.05096)

