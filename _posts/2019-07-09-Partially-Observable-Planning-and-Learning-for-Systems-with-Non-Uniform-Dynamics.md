---
layout: post
title: "Partially Observable Planning and Learning for Systems with Non-Uniform Dynamics"
date: 2019-07-09 23:22:42
categories: arXiv_AI
tags: arXiv_AI
author: Nicholas Collins, Hanna Kurniawati
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a neural network architecture, called TransNet, that combines planning and model learning for solving Partially Observable Markov Decision Processes (POMDPs) with non-uniform system dynamics. The past decade has seen a substantial advancement in solving POMDP problems. However, constructing a suitable POMDP model remains difficult. Recently, neural network architectures have been proposed to alleviate the difficulty in acquiring such models. Although the results are promising, existing architectures restrict the type of system dynamics that can be learned --that is, system dynamics must be the same in all parts of the state space. TransNet relaxes such a restriction. Key to this relaxation is a novel neural network module that classifies the state space into classes and then learns the system dynamics of the different classes. TransNet uses this module together with the overall architecture of QMDP-Net[1] to allow solving POMDPs that have more expressive dynamic models, while maintaining efficient data requirement. Its evaluation on typical benchmarks in robot navigation with initially unknown system and environment models indicates that TransNet substantially out-performs the quality of the generated policies and learning efficiency of the state-of-the-art method QMDP-Net.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.04457](http://arxiv.org/abs/1907.04457)

##### PDF
[http://arxiv.org/pdf/1907.04457](http://arxiv.org/pdf/1907.04457)

