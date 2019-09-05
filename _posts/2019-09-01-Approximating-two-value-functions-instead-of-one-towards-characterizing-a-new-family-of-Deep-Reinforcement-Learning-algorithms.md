---
layout: post
title: "Approximating two value functions instead of one: towards characterizing a new family of Deep Reinforcement Learning algorithms"
date: 2019-09-01 10:29:54
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Matthia Sabatelli, Gilles Louppe, Pierre Geurts, Marco A. Wiering
mathjax: true
---

* content
{:toc}

##### Abstract
This paper makes one step forward towards characterizing a new family of \textit{model-free} Deep Reinforcement Learning (DRL) algorithms. The aim of these algorithms is to jointly learn an approximation of the state-value function ($V$), alongside an approximation of the state-action value function ($Q$). Our analysis starts with a thorough study of the Deep Quality-Value Learning (DQV) algorithm, a DRL algorithm which has been shown to outperform popular techniques such as Deep-Q-Learning (DQN) and Double-Deep-Q-Learning (DDQN) \cite{sabatelli2018deep}. Intending to investigate why DQV's learning dynamics allow this algorithm to perform so well, we formulate a set of research questions which help us characterize a new family of DRL algorithms. Among our results, we present some specific cases in which DQV's performance can get harmed and introduce a novel \textit{off-policy} DRL algorithm, called DQV-Max, which can outperform DQV. We then study the behavior of the $V$ and $Q$ functions that are learned by DQV and DQV-Max and show that both algorithms might perform so well on several DRL test-beds because they are less prone to suffer from the overestimation bias of the $Q$ function.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.01779](http://arxiv.org/abs/1909.01779)

##### PDF
[http://arxiv.org/pdf/1909.01779](http://arxiv.org/pdf/1909.01779)

