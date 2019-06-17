---
layout: post
title: "Sub-policy Adaptation for Hierarchical Reinforcement Learning"
date: 2019-06-13 16:59:48
categories: arXiv_AI
tags: arXiv_AI Sparse Reinforcement_Learning Optimization
author: Alexander C. Li, Carlos Florensa, Ignasi Clavera, Pieter Abbeel
mathjax: true
---

* content
{:toc}

##### Abstract
Hierarchical Reinforcement Learning is a promising approach to long-horizon decision-making problems with sparse rewards. Unfortunately, most methods still decouple the lower-level skill acquisition process and the training of a higher level that controls the skills in a new task. Treating the skills as fixed can lead to significant sub-optimality in the transfer setting. In this work, we propose a novel algorithm to discover a set of skills, and continuously adapt them along with the higher level even when training on a new task. Our main contributions are two-fold. First, we derive a new hierarchical policy gradient, as well as an unbiased latent-dependent baseline. We introduce Hierarchical Proximal Policy Optimization (HiPPO), an on-policy method to efficiently train all levels of the hierarchy simultaneously. Second, we propose a method of training time-abstractions that improves the robustness of the obtained skills to environment changes. Code and results are available at sites.google.com/view/hippo-rl .

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.05862](http://arxiv.org/abs/1906.05862)

##### PDF
[http://arxiv.org/pdf/1906.05862](http://arxiv.org/pdf/1906.05862)

