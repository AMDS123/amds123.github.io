---
layout: post
title: "Informed MCMC with Bayesian Neural Networks for Facial Image Analysis"
date: 2018-11-19 20:47:04
categories: arXiv_CV
tags: arXiv_CV Inference
author: Adam Kortylewski, Mario Wieser, Andreas Morel-Forster, Aleksander Wieczorek, Sonali Parbhoo, Volker Roth, Thomas Vetter
mathjax: true
---

* content
{:toc}

##### Abstract
Computer vision tasks are difficult because of the large variability in the data that is induced by changes in light, background, partial occlusion as well as the varying pose, texture, and shape of objects. Generative approaches to computer vision allow us to overcome this difficulty by explicitly modeling the physical image formation process. Using generative object models, the analysis of an observed image is performed via Bayesian inference of the posterior distribution. This conceptually simple approach tends to fail in practice because of several difficulties stemming from sampling the posterior distribution: high-dimensionality and multi-modality of the posterior distribution as well as expensive simulation of the rendering process. The main difficulty of sampling approaches in a computer vision context is choosing the proposal distribution accurately so that maxima of the posterior are explored early and the algorithm quickly converges to a valid image interpretation. In this work, we propose to use a Bayesian Neural Network for estimating an image dependent proposal distribution. Compared to a standard Gaussian random walk proposal, this accelerates the sampler in finding regions of the posterior with high value. In this way, we can significantly reduce the number of samples needed to perform facial image analysis.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.07969](http://arxiv.org/abs/1811.07969)

##### PDF
[http://arxiv.org/pdf/1811.07969](http://arxiv.org/pdf/1811.07969)

