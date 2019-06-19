---
layout: post
title: "Visual Navigation by Generating Next Expected Observations"
date: 2019-06-17 18:14:03
categories: arXiv_CV
tags: arXiv_CV Inference
author: Qiaoyun Wu, Dinesh Manocha, Jun Wang, Kai Xu
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel approach to visual navigation in unknown environments where the agent is guided by conceiving the next observations it expects to see after taking the next best action. This is achieved by learning a variational Bayesian model that generates the next expected observations (NEO) conditioned on the current observations of the agent and the target view. Our approach predicts the next best action based on the current observation and NEO. Our generative model is learned through optimizing a variational objective encompassing two key designs. First, the latent distribution is conditioned on current observations and target view, supporting model-based, target-driven navigation. Second, the latent space is modeled with a Mixture of Gaussians conditioned on the current observation and next best action. Our use of mixture-of-posteriors prior effectively alleviates the issue of over-regularized latent space, thus facilitating model generalization in novel scenes. Moreover, the NEO generation models the forward dynamics of the agent-environment interaction, which improves the quality of approximate inference and hence benefits data efficiency. We have conducted extensive evaluations on both real-world and synthetic benchmarks, and show that our model outperforms the state-of-the-art RL-based methods significantly in terms of success rate, data efficiency, and cross-scene generalization.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.07207](http://arxiv.org/abs/1906.07207)

##### PDF
[http://arxiv.org/pdf/1906.07207](http://arxiv.org/pdf/1906.07207)

