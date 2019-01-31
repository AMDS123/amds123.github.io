---
layout: post
title: "Transfer in Deep Reinforcement Learning Using Successor Features and Generalised Policy Improvement"
date: 2019-01-30 17:30:31
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Deep_Learning
author: Andr&#xe9; Barreto, Diana Borsa, John Quan, Tom Schaul, David Silver, Matteo Hessel, Daniel Mankowitz, Augustin &#x17d;&#xed;dek, R&#xe9;mi Munos
mathjax: true
---

* content
{:toc}

##### Abstract
The ability to transfer skills across tasks has the potential to scale up reinforcement learning (RL) agents to environments currently out of reach. Recently, a framework based on two ideas, successor features (SFs) and generalised policy improvement (GPI), has been introduced as a principled way of transferring skills. In this paper we extend the SFs &amp; GPI framework in two ways. One of the basic assumptions underlying the original formulation of SFs &amp; GPI is that rewards for all tasks of interest can be computed as linear combinations of a fixed set of features. We relax this constraint and show that the theoretical guarantees supporting the framework can be extended to any set of tasks that only differ in the reward function. Our second contribution is to show that one can use the reward functions themselves as features for future tasks, without any loss of expressiveness, thus removing the need to specify a set of features beforehand. This makes it possible to combine SFs &amp; GPI with deep learning in a more stable way. We empirically verify this claim on a complex 3D environment where observations are images from a first-person perspective. We show that the transfer promoted by SFs &amp; GPI leads to very good policies on unseen tasks almost instantaneously. We also describe how to learn policies specialised to the new tasks in a way that allows them to be added to the agent's set of skills, and thus be reused in the future.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.10964](http://arxiv.org/abs/1901.10964)

##### PDF
[http://arxiv.org/pdf/1901.10964](http://arxiv.org/pdf/1901.10964)

