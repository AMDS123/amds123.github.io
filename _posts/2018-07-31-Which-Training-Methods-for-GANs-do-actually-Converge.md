---
layout: post
title: "Which Training Methods for GANs do actually Converge?"
date: 2018-07-31 16:28:15
categories: arXiv_CV
tags: arXiv_CV Regularization GAN
author: Lars Mescheder, Andreas Geiger, Sebastian Nowozin
mathjax: true
---

* content
{:toc}

##### Abstract
Recent work has shown local convergence of GAN training for absolutely continuous data and generator distributions. In this paper, we show that the requirement of absolute continuity is necessary: we describe a simple yet prototypical counterexample showing that in the more realistic case of distributions that are not absolutely continuous, unregularized GAN training is not always convergent. Furthermore, we discuss regularization strategies that were recently proposed to stabilize GAN training. Our analysis shows that GAN training with instance noise or zero-centered gradient penalties converges. On the other hand, we show that Wasserstein-GANs and WGAN-GP with a finite number of discriminator updates per generator update do not always converge to the equilibrium point. We discuss these results, leading us to a new explanation for the stability problems of GAN training. Based on our analysis, we extend our convergence results to more general GANs and prove local convergence for simplified gradient penalties even if the generator and data distribution lie on lower dimensional manifolds. We find these penalties to work well in practice and use them to learn high-resolution generative image models for a variety of datasets with little hyperparameter tuning.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1801.04406](https://arxiv.org/abs/1801.04406)

##### PDF
[https://arxiv.org/pdf/1801.04406](https://arxiv.org/pdf/1801.04406)

