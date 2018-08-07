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
最近提出的强化学习分布式方法（DiRL）的核心是学习奖励分配的分布，通常称为价值分配。在这项工作中，我们表明驱动DiRL方法的分布式Bellman方程等同于生成对抗网络（GAN）模型。在这个公式中，DiRL可以被视为学习价值分布的深层生成模型，由当前价值分布与当前奖励和下一个价值之和的分布驱动。我们利用这种洞察力提出了一种基于GAN的DiRL方法，该方法利用GAN的优势来学习高维数据的分布。特别是，我们表明我们的GAN方法可以用于具有多元奖励的DiRL，这是一个无法用现有方法解决的重要设置。多变量设置还允许我们统一学习值和状态转换的分布，并且我们利用这个想法来设计一种新的探索方法，该方法由估计值和状态的差异驱动。

##### URL
[https://arxiv.org/abs/1808.01960](https://arxiv.org/abs/1808.01960)

##### PDF
[https://arxiv.org/pdf/1808.01960](https://arxiv.org/pdf/1808.01960)

