---
layout: post
title: "Meta Reinforcement Learning with Distribution of Exploration Parameters Learned by Evolution Strategies"
date: 2018-12-29 08:40:38
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Yiming Shen, Kehan Yang, Yufeng Yuan, Simon Cheng Liu
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel meta-learning method in a reinforcement learning setting, based on evolution strategies (ES), exploration in parameter space and deterministic policy gradients. ES methods are easy to parallelize, which is desirable for modern training architectures; however, such methods typically require a huge number of samples for effective training. We use deterministic policy gradients during adaptation and other techniques to compensate for the sample-efficiency problem while maintaining the inherent scalability of ES methods. We demonstrate that our method achieves good results compared to gradient-based meta-learning in high-dimensional control tasks in the MuJoCo simulator. In addition, because of gradient-free methods in the meta-training phase, which do not need information about gradients and policies in adaptation training, we predict and confirm our algorithm performs better in tasks that need multi-step adaptation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.11314](http://arxiv.org/abs/1812.11314)

##### PDF
[http://arxiv.org/pdf/1812.11314](http://arxiv.org/pdf/1812.11314)

