---
layout: post
title: "Unsupervised Low Latency Speech Enhancement with RT-GCC-NMF"
date: 2019-04-05 15:54:38
categories: arXiv_SD
tags: arXiv_SD Relation
author: Sean U. N. Wood, Jean Rouat
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present RT-GCC-NMF: a real-time (RT), two-channel blind speech enhancement algorithm that combines the non-negative matrix factorization (NMF) dictionary learning algorithm with the generalized cross-correlation (GCC) spatial localization method. Using a pre-learned universal NMF dictionary, RT-GCC-NMF operates in a frame-by-frame fashion by associating individual dictionary atoms to target speech or background interference based on their estimated time-delay of arrivals (TDOA). We evaluate RT-GCC-NMF on two-channel mixtures of speech and real-world noise from the Signal Separation and Evaluation Campaign (SiSEC). We demonstrate that this approach generalizes to new speakers, acoustic environments, and recording setups from very little training data, and outperforms all but one of the algorithms from the SiSEC challenge in terms of overall Perceptual Evaluation methods for Audio Source Separation (PEASS) scores and compares favourably to the ideal binary mask baseline. Over a wide range of input SNRs, we show that this approach simultaneously improves the PEASS and signal to noise ratio (SNR)-based Blind Source Separation (BSS) Eval objective quality metrics as well as the short-time objective intelligibility (STOI) and extended STOI (ESTOI) objective speech intelligibility metrics. A flexible, soft masking function in the space of NMF activation coefficients offers real-time control of the trade-off between interference suppression and target speaker fidelity. Finally, we use an asymmetric short-time Fourier transform (STFT) to reduce the inherent algorithmic latency of RT-GCC-NMF from 64 ms to 2 ms with no loss in performance. We demonstrate that latencies within the tolerable range for hearing aids are possible on current hardware platforms.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1904.03130](https://arxiv.org/abs/1904.03130)

##### PDF
[https://arxiv.org/pdf/1904.03130](https://arxiv.org/pdf/1904.03130)

