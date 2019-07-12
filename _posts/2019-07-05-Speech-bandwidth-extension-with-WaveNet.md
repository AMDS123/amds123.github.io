---
layout: post
title: "Speech bandwidth extension with WaveNet"
date: 2019-07-05 20:17:31
categories: arXiv_SD
tags: arXiv_SD
author: Archit Gupta, Brendan Shillingford, Yannis Assael, Thomas C. Walters
mathjax: true
---

* content
{:toc}

##### Abstract
Large-scale mobile communication systems tend to contain legacy transmission channels with narrowband bottlenecks, resulting in characteristic "telephone-quality" audio. While higher quality codecs exist, due to the scale and heterogeneity of the networks, transmitting higher sample rate audio with modern high-quality audio codecs can be difficult in practice. This paper proposes an approach where a communication node can instead extend the bandwidth of a band-limited incoming speech signal that may have been passed through a low-rate codec. To this end, we propose a WaveNet-based model conditioned on a log-mel spectrogram representation of a bandwidth-constrained speech audio signal of 8 kHz and audio with artifacts from GSM full-rate (FR) compression to reconstruct the higher-resolution signal. In our experimental MUSHRA evaluation, we show that a model trained to upsample to 24kHz speech signals from audio passed through the 8kHz GSM-FR codec is able to reconstruct audio only slightly lower in quality to that of the Adaptive Multi-Rate Wideband audio codec (AMR-WB) codec at 16kHz, and closes around half the gap in perceptual quality between the original encoded signal and the original speech sampled at 24kHz. We further show that when the same model is passed 8kHz audio that has not been compressed, is able to again reconstruct audio of slightly better quality than 16kHz AMR-WB, in the same MUSHRA evaluation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.04927](http://arxiv.org/abs/1907.04927)

##### PDF
[http://arxiv.org/pdf/1907.04927](http://arxiv.org/pdf/1907.04927)

