---
layout: post
title: "Surprising Negative Results for Generative Adversarial Tree Search"
date: 2018-11-28 07:09:45
categories: arXiv_AI
tags: arXiv_AI Adversarial GAN Reinforcement_Learning
author: Kamyar Azizzadenesheli, Brandon Yang, Weitang Liu, Emma Brunskill, Zachary C Lipton, Animashree Anandkumar
mathjax: true
---

* content
{:toc}

##### Abstract
While many recent advances in deep reinforcement learning rely on model-free methods, model-based approaches remain an alluring prospect for their potential to exploit unsupervised data to learn environment dynamics. One prospect is to pursue hybrid approaches, as in AlphaGo, which combines Monte-Carlo Tree Search (MCTS)-a model-based method-with deep-Q networks (DQNs)-a model-free method. MCTS requires generating rollouts, which is computationally expensive. In this paper, we propose to simulate roll-outs, exploiting the latest breakthroughs in image-to-image transduction, namely Pix2Pix GANs, to predict the dynamics of the environment. Our proposed algorithm, generative adversarial tree search (GATS), simulates rollouts up to a specified depth using both a GAN- based dynamics model and a reward predictor. GATS employs MCTS for planning over the simulated samples and uses DQN to estimate the Q-function at the leaf states. Our theoretical analysis establishes some favorable properties of GATS vis-a-vis the bias-variance trade-off and empirical results show that on 5 popular Atari games, the dynamics and reward predictors converge quickly to accurate solutions. However, GATS fails to outperform DQNs in 4 out of 5 games. Notably, in these experiments, MCTS has only short rollouts (up to tree depth 4), while previous successes of MCTS have involved tree depth in the hundreds. We present a hypothesis for why tree search with short rollouts can fail even given perfect modeling.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1806.05780](http://arxiv.org/abs/1806.05780)

##### PDF
[http://arxiv.org/pdf/1806.05780](http://arxiv.org/pdf/1806.05780)

