---
layout: post
title: "Self-Imitation Learning of Locomotion Movements through Termination Curriculum"
date: 2019-07-27 04:08:30
categories: arXiv_RO
tags: arXiv_RO Reinforcement_Learning
author: Amin Babadi, Kourosh Naderi, Perttu H&#xe4;m&#xe4;l&#xe4;inen
mathjax: true
---

* content
{:toc}

##### Abstract
Animation and machine learning research have shown great advancements in the past decade, leading to robust and powerful methods for learning complex physically-based animations. However, learning can take hours or days, especially if no reference movement data is available. In this paper, we propose and evaluate a novel combination of techniques for accelerating the learning of stable locomotion movements through self-imitation learning of synthetic animations. First, we produce synthetic and cyclic reference movement using a recent online tree search approach that can discover stable walking gaits in a few minutes. This allows us to use reinforcement learning with Reference State Initialization (RSI) to find a neural network controller for imitating the synthesized reference motion. We further accelerate the learning using a novel curriculum learning approach called Termination Curriculum (TC), that adapts the episode termination threshold over time. The combination of the RSI and TC ensures that simulation budget is not wasted in regions of the state space not visited by the final policy. As a result, our agents can learn locomotion skills in just a few hours on a modest 4-core computer. We demonstrate this by producing locomotion movements for a variety of characters.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.11842](http://arxiv.org/abs/1907.11842)

##### PDF
[http://arxiv.org/pdf/1907.11842](http://arxiv.org/pdf/1907.11842)

