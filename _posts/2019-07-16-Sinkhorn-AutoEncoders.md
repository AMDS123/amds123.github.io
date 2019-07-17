---
layout: post
title: "Sinkhorn AutoEncoders"
date: 2019-07-16 02:04:33
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Giorgio Patrini, Rianne van den Berg, Patrick Forr&#xe9;, Marcello Carioni, Samarth Bhargav, Max Welling, Tim Genewein, Frank Nielsen
mathjax: true
---

* content
{:toc}

##### Abstract
Optimal transport offers an alternative to maximum likelihood for learning generative autoencoding models. We show that minimizing the p-Wasserstein distance between the generator and the true data distribution is equivalent to the unconstrained min-min optimization of the p-Wasserstein distance between the encoder aggregated posterior and the prior in latent space, plus a reconstruction error. We also identify the role of its trade-off hyperparameter as the capacity of the generator: its Lipschitz constant. Moreover, we prove that optimizing the encoder over any class of universal approximators, such as deterministic neural networks, is enough to come arbitrarily close to the optimum. We therefore advertise this framework, which holds for any metric space and prior, as a sweet-spot of current generative autoencoding objectives. We then introduce the Sinkhorn auto-encoder (SAE), which approximates and minimizes the p-Wasserstein distance in latent space via backprogation through the Sinkhorn algorithm. SAE directly works on samples, i.e. it models the aggregated posterior as an implicit distribution, with no need for a reparameterization trick for gradients estimations. SAE is thus able to work with different metric spaces and priors with minimal adaptations. We demonstrate the flexibility of SAE on latent spaces with different geometries and priors and compare with other methods on benchmark data sets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.01118](http://arxiv.org/abs/1810.01118)

##### PDF
[http://arxiv.org/pdf/1810.01118](http://arxiv.org/pdf/1810.01118)

