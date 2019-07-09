---
layout: post
title: "Learning a Behavioral Repertoire from Demonstrations"
date: 2019-07-05 23:08:08
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Niels Justesen, Miguel Gonzalez Duque, Daniel Cabarcas Jaramillo, Jean-Baptiste Mouret, Sebastian Risi
mathjax: true
---

* content
{:toc}

##### Abstract
Imitation Learning (IL) is a machine learning approach to learn a policy from a dataset of demonstrations. IL can be useful to kick-start learning before applying reinforcement learning (RL) but it can also be useful on its own, e.g. to learn to imitate human players in video games. However, a major limitation of current IL approaches is that they learn only a single "average" policy based on a dataset that possibly contains demonstrations of numerous different types of behaviors. In this paper, we propose a new approach called Behavioral Repertoire Imitation Learning (BRIL) that instead learns a repertoire of behaviors from a set of demonstrations by augmenting the state-action pairs with behavioral descriptions. The outcome of this approach is a single neural network policy conditioned on a behavior description that can be precisely modulated. We apply this approach to train a policy on 7,777 human replays to perform build-order planning in StarCraft II. Principal Component Analysis (PCA) is applied to construct a low-dimensional behavioral space from the high-dimensional army unit composition of each demonstration. The results demonstrate that the learned policy can be effectively manipulated to express distinct behaviors. Additionally, by applying the UCB1 algorithm, we are able to adapt the behavior of the policy - in-between games - to reach a performance beyond that of the traditional IL baseline approach.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.03046](http://arxiv.org/abs/1907.03046)

##### PDF
[http://arxiv.org/pdf/1907.03046](http://arxiv.org/pdf/1907.03046)

