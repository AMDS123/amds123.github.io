---
layout: post
title: "Iterative Channel Estimation for Discrete Denoising under Channel Uncertainty"
date: 2019-02-24 10:58:39
categories: arXiv_AI
tags: arXiv_AI
author: Hongjoon Ahn, Taesup Moon
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel iterative channel estimation (ICE) algorithm that essentially removes the critical known noisy channel assumption for universal discrete denoising problem. Our algorithm is based on Neural DUDE (N-DUDE), a recently proposed neural network-based discrete denoiser, and it estimates the channel transition matrix as well as the neural network parameters in an alternating manner until convergence. While we do not make any probabilistic assumption on the underlying clean data, our ICE resembles Expectation-Maximization (EM) with variational approximation, and it takes advantage of the property of N-DUDE being locally robust around the true channel. With extensive experiments on several radically different types of data, we show that the ICE equipped N-DUDE (dubbed as ICE-N-DUDE) can perform \emph{universally} well regardless of the uncertainties in both the channel and the clean source. Moreover, we show ICE-N-DUDE becomes extremely robust to its hyperparameters and significantly outperforms the strong baseline that can deal with the channel uncertainties for denoising, the widely used Baum-Welch (BW) algorithm for hidden Markov models (HMM).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.08921](http://arxiv.org/abs/1902.08921)

##### PDF
[http://arxiv.org/pdf/1902.08921](http://arxiv.org/pdf/1902.08921)

