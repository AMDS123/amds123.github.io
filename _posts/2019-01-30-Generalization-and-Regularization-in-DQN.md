---
layout: post
title: "Generalization and Regularization in DQN"
date: 2019-01-30 17:59:21
categories: arXiv_AI
tags: arXiv_AI Regularization Reinforcement_Learning
author: Jesse Farebrother, Marlos C. Machado, Michael Bowling
mathjax: true
---

* content
{:toc}

##### Abstract
Deep reinforcement learning (RL) algorithms have shown an impressive ability to learn complex control policies in high-dimensional environments. However, despite the ever-increasing performance on popular benchmarks such as the Arcade Learning Environment (ALE), policies learned by deep RL algorithms often struggle to generalize when evaluated in remarkably similar environments. In this paper, we assess the generalization capabilities of DQN, one of the most traditional deep RL algorithms in the field. We provide evidence suggesting that DQN overspecializes to the training environment. We comprehensively evaluate the impact of traditional regularization methods, $\ell_2$-regularization and dropout, and of reusing the learned representations to improve the generalization capabilities of DQN. We perform this study using different game modes of Atari 2600 games, a recently introduced modification for the ALE which supports slight variations of the Atari 2600 games traditionally used for benchmarking. Despite regularization being largely underutilized in deep RL, we show that it can, in fact, help DQN learn more general features. These features can then be reused and fine-tuned on similar tasks, considerably improving the sample efficiency of DQN.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.00123](http://arxiv.org/abs/1810.00123)

##### PDF
[http://arxiv.org/pdf/1810.00123](http://arxiv.org/pdf/1810.00123)

