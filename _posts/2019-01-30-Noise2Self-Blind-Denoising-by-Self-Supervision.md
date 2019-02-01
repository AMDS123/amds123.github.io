---
layout: post
title: "Noise2Self: Blind Denoising by Self-Supervision"
date: 2019-01-30 18:05:47
categories: arXiv_CV
tags: arXiv_CV Detection
author: Joshua Batson, Loic Royer
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a general framework for denoising high-dimensional measurements which requires no prior on the signal, no estimate of the noise, and no clean training data. The only assumption is that the noise exhibits statistical independence across different dimensions of the measurement. Moreover, our framework is not restricted to a particular denoising model. We show how it can be used to calibrate any parameterised denoising algorithm, from the single hyperparameter of a median filter to the millions of weights of a deep neural network. We demonstrate this on natural image and microscopy data, where we exploit noise independence between pixels, and on single-cell gene expression data, where we exploit independence between detections of individual molecules. Finally, we prove a theoretical lower bound on the performance of an optimal denoiser. This framework generalizes recent work on training neural nets from noisy images and on cross-validation for matrix factorization.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.11365](http://arxiv.org/abs/1901.11365)

##### PDF
[http://arxiv.org/pdf/1901.11365](http://arxiv.org/pdf/1901.11365)

