---
layout: post
title: "An investigation of model-free planning"
date: 2019-01-11 11:42:51
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning CNN RNN
author: Arthur Guez, Mehdi Mirza, Karol Gregor, Rishabh Kabra, S&#xe9;bastien Racani&#xe8;re, Th&#xe9;ophane Weber, David Raposo, Adam Santoro, Laurent Orseau, Tom Eccles, Greg Wayne, David Silver, Timothy Lillicrap
mathjax: true
---

* content
{:toc}

##### Abstract
The field of reinforcement learning (RL) is facing increasingly challenging domains with combinatorial complexity. For an RL agent to address these challenges, it is essential that it can plan effectively. Prior work has typically utilized an explicit model of the environment, combined with a specific planning algorithm (such as tree search). More recently, a new family of methods have been proposed that learn how to plan, by providing the structure for planning via an inductive bias in the function approximator (such as a tree structured neural network), trained end-to-end by a model-free RL algorithm. In this paper, we go even further, and demonstrate empirically that an entirely model-free approach, without special structure beyond standard neural network components such as convolutional networks and LSTMs, can learn to exhibit many of the characteristics typically associated with a model-based planner. We measure our agent's effectiveness at planning in terms of its ability to generalize across a combinatorial and irreversible state space, its data efficiency, and its ability to utilize additional thinking time. We find that our agent has many of the characteristics that one might expect to find in a planning algorithm. Furthermore, it exceeds the state-of-the-art in challenging combinatorial domains such as Sokoban and outperforms other model-free approaches that utilize strong inductive biases toward planning.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.03559](http://arxiv.org/abs/1901.03559)

##### PDF
[http://arxiv.org/pdf/1901.03559](http://arxiv.org/pdf/1901.03559)

