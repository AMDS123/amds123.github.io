---
layout: post
title: "Learning Sampling Distributions for Robot Motion Planning"
date: 2019-03-12 02:40:29
categories: arXiv_RO
tags: arXiv_RO
author: Brian Ichter, James Harrison, Marco Pavone
mathjax: true
---

* content
{:toc}

##### Abstract
A defining feature of sampling-based motion planning is the reliance on an implicit representation of the state space, which is enabled by a set of probing samples. Traditionally, these samples are drawn either probabilistically or deterministically to uniformly cover the state space. Yet, the motion of many robotic systems is often restricted to "small" regions of the state space, due to, for example, differential constraints or collision-avoidance constraints. To accelerate the planning process, it is thus desirable to devise non-uniform sampling strategies that favor sampling in those regions where an optimal solution might lie. This paper proposes a methodology for non-uniform sampling, whereby a sampling distribution is learned from demonstrations, and then used to bias sampling. The sampling distribution is computed through a conditional variational autoencoder, allowing sample generation from the latent space conditioned on the specific planning problem. This methodology is general, can be used in combination with any sampling-based planner, and can effectively exploit the underlying structure of a planning problem while maintaining the theoretical guarantees of sampling-based approaches. Specifically, on several planning problems, the proposed methodology is shown to effectively learn representations for the relevant regions of the state space, resulting in an order of magnitude improvement in terms of success rate and convergence to the optimal cost.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1709.05448](http://arxiv.org/abs/1709.05448)

##### PDF
[http://arxiv.org/pdf/1709.05448](http://arxiv.org/pdf/1709.05448)

