---
layout: post
title: "Expected Sarsa with Control Variate for Variance Reduction"
date: 2019-06-25 11:35:44
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Long Yang, Yu Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Off-policy learning is powerful for reinforcement learning. However, the high variance of off-policy evaluation is a critical challenge, which causes off-policy learning with function approximation falls into an uncontrolled instability. In this paper, for reducing the variance, we introduce control variate technique to Expected Sarsa($\lambda$) and propose a tabular ES($\lambda$)-CV algorithm. We prove that if a proper estimator of value function reaches, the proposed ES($\lambda$)-CV enjoys a lower variance than Expected Sarsa($\lambda$). Furthermore, to extend ES($\lambda$)-CV to be a convergent algorithm with linear function approximation, we propose the GES($\lambda$) algorithm under the convex-concave saddle-point formulation. We prove that the convergence rate of GES($\lambda$) achieves $\mathcal{O}(1/T)$, which matches or outperforms several state-of-art gradient-based algorithms, but we use a more relaxed step-size. Numerical experiments show that the proposed algorithm is stable and converges faster with lower variance than several state-of-art gradient-based TD learning algorithms: GQ($\lambda$), GTB($\lambda$) and ABQ($\zeta$).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.11058](http://arxiv.org/abs/1906.11058)

##### PDF
[http://arxiv.org/pdf/1906.11058](http://arxiv.org/pdf/1906.11058)

