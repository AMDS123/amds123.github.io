---
layout: post
title: "Towards Characterizing Divergence in Deep Q-Learning"
date: 2019-03-21 09:42:41
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Joshua Achiam, Ethan Knight, Pieter Abbeel
mathjax: true
---

* content
{:toc}

##### Abstract
Deep Q-Learning (DQL), a family of temporal difference algorithms for control, employs three techniques collectively known as the `deadly triad' in reinforcement learning: bootstrapping, off-policy learning, and function approximation. Prior work has demonstrated that together these can lead to divergence in Q-learning algorithms, but the conditions under which divergence occurs are not well-understood. In this note, we give a simple analysis based on a linear approximation to the Q-value updates, which we believe provides insight into divergence under the deadly triad. The central point in our analysis is to consider when the leading order approximation to the deep-Q update is or is not a contraction in the sup norm. Based on this analysis, we develop an algorithm which permits stable deep Q-learning for continuous control without any of the tricks conventionally used (such as target networks, adaptive gradient optimizers, or using multiple Q functions). We demonstrate that our algorithm performs above or near state-of-the-art on standard MuJoCo benchmarks from the OpenAI Gym.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.08894](http://arxiv.org/abs/1903.08894)

##### PDF
[http://arxiv.org/pdf/1903.08894](http://arxiv.org/pdf/1903.08894)

