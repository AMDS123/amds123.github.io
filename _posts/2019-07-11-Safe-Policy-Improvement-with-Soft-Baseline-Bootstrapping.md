---
layout: post
title: "Safe Policy Improvement with Soft Baseline Bootstrapping"
date: 2019-07-11 09:59:10
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Optimization
author: Kimia Nadjahi, Romain Laroche, R&#xe9;mi Tachet des Combes
mathjax: true
---

* content
{:toc}

##### Abstract
Batch Reinforcement Learning (Batch RL) consists in training a policy using trajectories collected with another policy, called the behavioural policy. Safe policy improvement (SPI) provides guarantees with high probability that the trained policy performs better than the behavioural policy, also called baseline in this setting. Previous work shows that the SPI objective improves mean performance as compared to using the basic RL objective, which boils down to solving the MDP with maximum likelihood. Here, we build on that work and improve more precisely the SPI with Baseline Bootstrapping algorithm (SPIBB) by allowing the policy search over a wider set of policies. Instead of binarily classifying the state-action pairs into two sets (the \textit{uncertain} and the \textit{safe-to-train-on} ones), we adopt a softer strategy that controls the error in the value estimates by constraining the policy change according to the local model uncertainty. The method can take more risks on uncertain actions all the while remaining provably-safe, and is therefore less conservative than the state-of-the-art methods. We propose two algorithms (one optimal and one approximate) to solve this constrained optimization problem and empirically show a significant improvement over existing SPI algorithms both on finite MDPs and on infinite MDPs with a neural network function approximation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.05079](http://arxiv.org/abs/1907.05079)

##### PDF
[http://arxiv.org/pdf/1907.05079](http://arxiv.org/pdf/1907.05079)

