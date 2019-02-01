---
layout: post
title: "End-to-End Probabilistic Inference for Nonstationary Audio Analysis"
date: 2019-01-31 15:47:47
categories: arXiv_SD
tags: arXiv_SD Inference
author: William J. Wilkinson, Michael Riis Andersen, Joshua D. Reiss, Dan Stowell, Arno Solin
mathjax: true
---

* content
{:toc}

##### Abstract
A typical audio signal processing pipeline includes multiple disjoint analysis stages, including calculation of a time-frequency representation followed by spectrogram-based feature analysis. We show how time-frequency analysis and nonnegative matrix factorisation can be jointly formulated as a spectral mixture Gaussian process model with nonstationary priors over the amplitude variance parameters. Further, we formulate this nonlinear model's state space representation, making it amenable to infinite-horizon Gaussian process regression with approximate inference via expectation propagation, which scales linearly in the number of time steps and quadratically in the state dimensionality. By doing so, we are able to process audio signals with hundreds of thousands of data points. We demonstrate, on various tasks with empirical data, how this inference scheme outperforms more standard techniques that rely on extended Kalman filtering.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.11436](http://arxiv.org/abs/1901.11436)

##### PDF
[http://arxiv.org/pdf/1901.11436](http://arxiv.org/pdf/1901.11436)

