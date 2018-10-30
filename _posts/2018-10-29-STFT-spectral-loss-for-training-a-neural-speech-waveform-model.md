---
layout: post
title: "STFT spectral loss for training a neural speech waveform model"
date: 2018-10-29 04:05:35
categories: arXiv_CL
tags: arXiv_CL RNN
author: Shinji Takaki, Toru Nakshika, Xin Wang, Junichi Yamagishi
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a new loss using short-time Fourier transform (STFT) spectra for the aim of training a high-performance neural speech waveform model that predicts raw continuous speech waveform samples directly. Not only amplitude spectra but also phase spectra obtained from generated speech waveforms are used to calculate the proposed loss. We also mathematically show that training of the waveform model on the basis of the proposed loss can be interpreted as maximum likelihood training that assumes the amplitude and phase spectra of generated speech waveforms following Gaussian and von Mises distributions, respectively. Furthermore, this paper presents a simple network architecture as the speech waveform model, which is composed of uni-directional long short-term memories (LSTMs) and an auto-regressive structure. Experimental results showed that the proposed neural model synthesized high-quality speech waveforms.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.11945](http://arxiv.org/abs/1810.11945)

##### PDF
[http://arxiv.org/pdf/1810.11945](http://arxiv.org/pdf/1810.11945)

