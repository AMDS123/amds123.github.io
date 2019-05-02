---
layout: post
title: "SAI, a Sensible Artificial Intelligence that plays Go"
date: 2019-05-01 08:16:29
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Francesco Morandin, Gianluca Amato, Rosa Gini, Carlo Metta, Maurizio Parton, Gian-Carlo Pascutto
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a multiple-komi modification of the AlphaGo Zero/Leela Zero paradigm. The winrate as a function of the komi is modeled with a two-parameters sigmoid function, so that the neural network must predict just one more variable to assess the winrate for all komi values. A second novel feature is that training is based on self-play games that occasionally branch -- with changed komi -- when the position is uneven. With this setting, reinforcement learning is showed to work on 7x7 Go, obtaining very strong playing agents. As a useful byproduct, the sigmoid parameters given by the network allow to estimate the score difference on the board, and to evaluate how much the game is decided.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1809.03928](http://arxiv.org/abs/1809.03928)

##### PDF
[http://arxiv.org/pdf/1809.03928](http://arxiv.org/pdf/1809.03928)

