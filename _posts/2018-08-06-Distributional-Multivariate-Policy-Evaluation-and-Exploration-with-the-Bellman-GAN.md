---
layout: post
title: "Distributional Multivariate Policy Evaluation and Exploration with the Bellman GAN"
date: 2018-08-06 15:22:13
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Reinforcement_Learning
author: Dror Freirich, Ron Meir, Aviv Tamar
mathjax: true
---

* content
{:toc}

##### Abstract
The recently proposed distributional approach to reinforcement learning (DiRL) is centered on learning the distribution of the reward-to-go, often referred to as the value distribution. In this work, we show that the distributional Bellman equation, which drives DiRL methods, is equivalent to a generative adversarial network (GAN) model. In this formulation, DiRL can be seen as learning a deep generative model of the value distribution, driven by the discrepancy between the distribution of the current value, and the distribution of the sum of current reward and next value. We use this insight to propose a GAN-based approach to DiRL, which leverages the strengths of GANs in learning distributions of high-dimensional data. In particular, we show that our GAN approach can be used for DiRL with multivariate rewards, an important setting which cannot be tackled with prior methods. The multivariate setting also allows us to unify learning the distribution of values and state transitions, and we exploit this idea to devise a novel exploration method that is driven by the discrepancy in estimating both values and states.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1808.01960](https://arxiv.org/abs/1808.01960)

##### PDF
[https://arxiv.org/pdf/1808.01960](https://arxiv.org/pdf/1808.01960)

