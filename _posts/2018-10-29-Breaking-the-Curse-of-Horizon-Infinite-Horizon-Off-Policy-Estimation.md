---
layout: post
title: "Breaking the Curse of Horizon: Infinite-Horizon Off-Policy Estimation"
date: 2018-10-29 22:03:58
categories: arXiv_AI
tags: arXiv_AI Face
author: Qiang Liu, Lihong Li, Ziyang Tang, Dengyong Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the off-policy estimation problem of estimating the expected reward of a target policy using samples collected by a different behavior policy. Importance sampling (IS) has been a key technique to derive (nearly) unbiased estimators, but is known to suffer from an excessively high variance in long-horizon problems. In the extreme case of in infinite-horizon problems, the variance of an IS-based estimator may even be unbounded. In this paper, we propose a new off-policy estimation method that applies IS directly on the stationary state-visitation distributions to avoid the exploding variance issue faced by existing estimators.Our key contribution is a novel approach to estimating the density ratio of two stationary distributions, with trajectories sampled from only the behavior distribution. We develop a mini-max loss function for the estimation problem, and derive a closed-form solution for the case of RKHS. We support our method with both theoretical and empirical analyses.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.12429](http://arxiv.org/abs/1810.12429)

##### PDF
[http://arxiv.org/pdf/1810.12429](http://arxiv.org/pdf/1810.12429)

