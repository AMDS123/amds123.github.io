---
layout: post
title: "End-to-End Multi-Task Denoising for joint SDR and PESQ Optimization"
date: 2019-01-26 02:48:08
categories: arXiv_SD
tags: arXiv_SD Optimization Relation
author: Jaeyoung Kim, Mostafa El-Kharmy, Jungwon Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Supervised learning based on a deep neural network recently has achieved substantial improvement on speech enhancement. Denoising networks learn mapping from noisy speech to clean one directly, or to a spectra mask which is the ratio between clean and noisy spectrum. In either case, the network is optimized by minimizing mean square error (MSE) between predefined labels and network output of spectra or time-domain signal. However, existing schemes have either of two critical issues: spectra and metric mismatches. The spectra mismatch is a well known issue that any spectra modification after short-time Fourier transform (STFT), in general, cannot be fully recovered after inverse STFT. The metric mismatch is that a conventional MSE metric is sub-optimal to maximize our target metrics, signal-to-distortion ratio (SDR) and perceptual evaluation of speech quality (PESQ). This paper presents a new end-to-end denoising framework with the goal of joint SDR and PESQ optimization. First, the network optimization is performed on the time-domain signals after ISTFT to avoid spectra mismatch. Second, two loss functions which have improved correlations with SDR and PESQ metrics are proposed to minimize metric mismatch. The experimental result showed that the proposed denoising scheme significantly improved both SDR and PESQ performance over the existing methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.09146](http://arxiv.org/abs/1901.09146)

##### PDF
[http://arxiv.org/pdf/1901.09146](http://arxiv.org/pdf/1901.09146)

