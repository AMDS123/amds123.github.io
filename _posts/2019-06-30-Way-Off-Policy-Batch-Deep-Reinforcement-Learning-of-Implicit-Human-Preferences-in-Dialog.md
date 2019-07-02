---
layout: post
title: "Way Off-Policy Batch Deep Reinforcement Learning of Implicit Human Preferences in Dialog"
date: 2019-06-30 20:53:19
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Natasha Jaques, Asma Ghandeharioun, Judy Hanwen Shen, Craig Ferguson, Agata Lapedriza, Noah Jones, Shixiang Gu, Rosalind Picard
mathjax: true
---

* content
{:toc}

##### Abstract
Most deep reinforcement learning (RL) systems are not able to learn effectively from off-policy data, especially if they cannot explore online in the environment. These are critical shortcomings for applying RL to real-world problems where collecting data is expensive, and models must be tested offline before being deployed to interact with the environment -- e.g. systems that learn from human interaction. Thus, we develop a novel class of off-policy batch RL algorithms, which are able to effectively learn offline, without exploring, from a fixed batch of human interaction data. We leverage models pre-trained on data as a strong prior, and use KL-control to penalize divergence from this prior during RL training. We also use dropout-based uncertainty estimates to lower bound the target Q-values as a more efficient alternative to Double Q-Learning. The algorithms are tested on the problem of open-domain dialog generation -- a challenging reinforcement learning problem with a 20,000-dimensional action space. Using our Way Off-Policy algorithm, we can extract multiple different reward functions post-hoc from collected human interaction data, and learn effectively from all of these. We test the real-world generalization of these systems by deploying them live to converse with humans in an open-domain setting, and demonstrate that our algorithm achieves significant improvements over prior methods in off-policy batch RL.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.00456](http://arxiv.org/abs/1907.00456)

##### PDF
[http://arxiv.org/pdf/1907.00456](http://arxiv.org/pdf/1907.00456)

