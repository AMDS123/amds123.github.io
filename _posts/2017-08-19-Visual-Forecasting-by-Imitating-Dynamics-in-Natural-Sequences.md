---
layout: post
title: "Visual Forecasting by Imitating Dynamics in Natural Sequences"
date: 2017-08-19 09:45:52
categories: arXiv_CV
tags: arXiv_CV Knowledge Reinforcement_Learning
author: Kuo-Hao Zeng, William B. Shen, De-An Huang, Min Sun, Juan Carlos Niebles
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a general framework for visual forecasting, which directly imitates visual sequences without additional supervision. As a result, our model can be applied at several semantic levels and does not require any domain knowledge or handcrafted features. We achieve this by formulating visual forecasting as an inverse reinforcement learning (IRL) problem, and directly imitate the dynamics in natural sequences from their raw pixel values. The key challenge is the high-dimensional and continuous state-action space that prohibits the application of previous IRL algorithms. We address this computational bottleneck by extending recent progress in model-free imitation with trainable deep feature representations, which (1) bypasses the exhaustive state-action pair visits in dynamic programming by using a dual formulation and (2) avoids explicit state sampling at gradient computation using a deep feature reparametrization. This allows us to apply IRL at scale and directly imitate the dynamics in high-dimensional continuous visual sequences from the raw pixel values. We evaluate our approach at three different level-of-abstraction, from low level pixels to higher level semantics: future frame generation, action anticipation, visual story forecasting. At all levels, our approach outperforms existing methods.

##### Abstract (translated by Google)
我们介绍了一个视觉预测的一般框架，它直接模仿视觉序列而不需要额外的监督。因此，我们的模型可以应用于多个语义层次，并且不需要任何领域知识或手工功能。我们通过将视觉预测作为逆强化学习（IRL）问题来实现这一点，并直接模仿自然序列的动态像素值。关键的挑战是禁止应用以前的IRL算法的高维连续状态动作空间。我们通过扩展最近在无模型模仿方面的进展来解决这个计算瓶颈问题，即使用可训练的深度特征表示，（1）通过使用双重制定绕过动态规划中详尽的状态动作对访问和（2）避免显式状态抽样计算使用深度特征reparametrization。这使我们能够按比例应用IRL，并直接模仿来自原始像素值的高维连续视觉序列的动态。我们从三个不同的抽象层次评估我们的方法，从低级像素到更高级别的语义：未来的帧生成，行动预测，视觉故事预测。在各个层面上，我们的方法都优于现有的方法。

##### URL
[https://arxiv.org/abs/1708.05827](https://arxiv.org/abs/1708.05827)

##### PDF
[https://arxiv.org/pdf/1708.05827](https://arxiv.org/pdf/1708.05827)

