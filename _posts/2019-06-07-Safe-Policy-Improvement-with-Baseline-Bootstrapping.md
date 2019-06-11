---
layout: post
title: "Safe Policy Improvement with Baseline Bootstrapping"
date: 2019-06-07 17:45:54
categories: arXiv_AI
tags: arXiv_AI Knowledge Reinforcement_Learning
author: Romain Laroche, Paul Trichelair, R&#xe9;mi Tachet des Combes
mathjax: true
---

* content
{:toc}

##### Abstract
This paper considers Safe Policy Improvement (SPI) in Batch Reinforcement Learning (Batch RL): from a fixed dataset and without direct access to the true environment, train a policy that is guaranteed to perform at least as well as the baseline policy used to collect the data. Our approach, called SPI with Baseline Bootstrapping (SPIBB), is inspired by the knows-what-it-knows paradigm: it bootstraps the trained policy with the baseline when the uncertainty is high. Our first algorithm, $\Pi_b$-SPIBB, comes with SPI theoretical guarantees. We also implement a variant, $\Pi_{\leq b}$-SPIBB, that is even more efficient in practice. We apply our algorithms to a motivational stochastic gridworld domain and further demonstrate on randomly generated MDPs the superiority of SPIBB with respect to existing algorithms, not only in safety but also in mean performance. Finally, we implement a model-free version of SPIBB and show its benefits on a navigation task with deep RL implementation called SPIBB-DQN, which is, to the best of our knowledge, the first RL algorithm relying on a neural network representation able to train efficiently and reliably from batch data, without any interaction with the environment.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1712.06924](http://arxiv.org/abs/1712.06924)

##### PDF
[http://arxiv.org/pdf/1712.06924](http://arxiv.org/pdf/1712.06924)

