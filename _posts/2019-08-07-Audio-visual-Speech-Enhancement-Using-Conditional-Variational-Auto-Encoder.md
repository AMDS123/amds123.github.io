---
layout: post
title: "Audio-visual Speech Enhancement Using Conditional Variational Auto-Encoder"
date: 2019-08-07 12:38:32
categories: arXiv_SD
tags: arXiv_SD Deep_Learning
author: Mostafa Sadeghi, Simon Leglaive, Xavier Alameda-PIneda, Laurent Girin, Radu Horaud
mathjax: true
---

* content
{:toc}

##### Abstract
Variational auto-encoders (VAEs) are deep generative latent variable models that can be used for learning the distribution of complex data. VAEs have been successfully used to learn a probabilistic prior over speech signals, which is then used to perform speech enhancement. One advantage of this generative approach is that it does not require pairs of clean and noisy speech signals at training. In this paper, we propose audio-visual variants of VAEs for single-channel and speaker-independent speech enhancement. We develop a conditional VAE (CVAE) where the audio speech generative process is conditioned on visual information of the lip region. At test time, the audio-visual speech generative model is combined with a noise model based on nonnegative matrix factorization, and speech enhancement relies on a Monte Carlo expectation-maximization algorithm. Experiments are conducted with the recently published NTCD-TIMIT dataset. The results confirm that the proposed audio-visual CVAE effectively fuse audio and visual information, and it improves the speech enhancement performance compared with the audio-only VAE model, especially when the speech signal is highly corrupted by noise. We also show that the proposed unsupervised audio-visual speech enhancement approach outperforms a state-of-the-art supervised deep learning method.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.02590](http://arxiv.org/abs/1908.02590)

##### PDF
[http://arxiv.org/pdf/1908.02590](http://arxiv.org/pdf/1908.02590)

