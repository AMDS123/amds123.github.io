---
layout: post
title: "Data-driven design of perfect reconstruction filterbank for DNN-based sound source enhancement"
date: 2019-03-21 08:50:12
categories: arXiv_SD
tags: arXiv_SD
author: Daiki Takeuchi, Kohei Yatabe, Yuma Koizumi, Yasuhiro Oikawa, Noboru Harada
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a data-driven design method of perfect-reconstruction filterbank (PRFB) for sound-source enhancement (SSE) based on deep neural network (DNN). DNNs have been used to estimate a time-frequency (T-F) mask in the short-time Fourier transform (STFT) domain. Their training is more stable when a simple cost function as mean-squared error (MSE) is utilized comparing to some advanced cost such as objective sound quality assessments. However, such a simple cost function inherits strong assumptions on the statistics of the target and/or noise which is often not satisfied, and the mismatch of assumption results in degraded performance. In this paper, we propose to design the frequency scale of PRFB from training data so that the assumption on MSE is satisfied. For designing the frequency scale, the warped filterbank frame (WFBF) is considered as PRFB. The frequency characteristic of learned WFBF was in between STFT and the wavelet transform, and its effectiveness was confirmed by comparison with a standard STFT-based DNN whose input feature is compressed into the mel scale.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.08876](http://arxiv.org/abs/1903.08876)

##### PDF
[http://arxiv.org/pdf/1903.08876](http://arxiv.org/pdf/1903.08876)

