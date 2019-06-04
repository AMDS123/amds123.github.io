---
layout: post
title: "Assumed Density Filtering Q-learning"
date: 2019-06-03 05:09:09
categories: arXiv_AI
tags: arXiv_AI Regularization Reinforcement_Learning Inference
author: Heejin Jeong, Clark Zhang, George J. Pappas, Daniel D. Lee
mathjax: true
---

* content
{:toc}

##### Abstract
While off-policy temporal difference (TD) methods have widely been used in reinforcement learning due to their efficiency and simple implementation, their Bayesian counterparts have not been utilized as frequently. One reason is that the non-linear max operation in the Bellman optimality equation makes it difficult to define conjugate distributions over the value functions. In this paper, we introduce a novel Bayesian approach to off-policy TD methods, called as ADFQ, which updates beliefs on state-action values, Q, through an online Bayesian inference method known as Assumed Density Filtering. We formulate an efficient closed-form solution for the value update by approximately estimating analytic parameters of the posterior of the Q-beliefs. Uncertainty measures in the beliefs not only are used in exploration but also provide a natural regularization for the value update considering all next available actions. ADFQ converges to Q-learning as the uncertainty measures of the Q-beliefs decrease and improves common drawbacks of other Bayesian RL algorithms such as computational complexity. We extend ADFQ with a neural network. Our empirical results demonstrate that ADFQ outperforms comparable algorithms on various Atari 2600 games, with drastic improvements in highly stochastic domains or domains with a large action space.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1712.03333](http://arxiv.org/abs/1712.03333)

##### PDF
[http://arxiv.org/pdf/1712.03333](http://arxiv.org/pdf/1712.03333)

