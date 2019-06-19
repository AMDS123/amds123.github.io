---
layout: post
title: "Integrated sidelobe cancellation and linear prediction Kalman filter for joint multi-microphone speech dereverberation, interfering speech cancellation, and noise reduction"
date: 2019-06-18 11:58:30
categories: arXiv_SD
tags: arXiv_SD Prediction
author: T. Dietzen, S. Doclo, M. Moonen, T. van Waterschoot
mathjax: true
---

* content
{:toc}

##### Abstract
In multi-microphone speech enhancement, reverberation as well as additive noise and/or interfering speech are commonly suppressed by deconvolution and spatial filtering, e.g., using multi-channel linear prediction (MCLP) on the one hand and beamforming, e.g., a generalized sidelobe canceler (GSC), on the other hand. In this paper, we consider several reverberant speech components, whereof some are to be dereverberated and others to be canceled, as well as a diffuse (e.g., babble) noise component to be suppressed. In order to perform both deconvolution and spatial filtering, we integrate MCLP and the GSC into a novel architecture referred to as integrated sidelobe cancellation and linear prediction (ISCLP), where the sidelobe-cancellation (SC) filter and the linear prediction (LP) filter operate in parallel, but on different microphone signal frames. Within ISCLP, we estimate both filters jointly by means of a single Kalman filter. We further propose a spectral Wiener gain post-processor, which is shown to relate to the Kalman filter's posterior state estimate. The presented ISCLP Kalman filter is benchmarked against two state-of-the-art approaches, namely first a pair of alternating Kalman filters respectively performing dereverberation and noise reduction, and second an MCLP+GSC Kalman filter cascade. While the ISCLP Kalman filter is roughly $M^2$ times less expensive than both reference algorithms, where $M$ denotes the number of microphones, it is shown to perform similarly as compared to the former, and to outperform the latter.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.07512](http://arxiv.org/abs/1906.07512)

##### PDF
[http://arxiv.org/pdf/1906.07512](http://arxiv.org/pdf/1906.07512)

