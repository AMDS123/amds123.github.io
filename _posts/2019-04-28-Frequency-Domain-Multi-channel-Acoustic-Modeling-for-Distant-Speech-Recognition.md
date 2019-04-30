---
layout: post
title: "Frequency Domain Multi-channel Acoustic Modeling for Distant Speech Recognition"
date: 2019-04-28 20:42:39
categories: arXiv_SD
tags: arXiv_SD Knowledge Speech_Recognition Optimization RNN Recognition
author: Minhua Wu, Kenichi Kumatani, Shiva Sundaram, Nikko Strom, Bjorn Hoffmeister
mathjax: true
---

* content
{:toc}

##### Abstract
Conventional far-field automatic speech recognition (ASR) systems typically employ microphone array techniques for speech enhancement in order to improve robustness against noise or reverberation. However, such speech enhancement techniques do not always yield ASR accuracy improvement because the optimization criterion for speech enhancement is not directly relevant to the ASR objective. In this work, we develop new acoustic modeling techniques that optimize spatial filtering and long short-term memory (LSTM) layers from multi-channel (MC) input based on an ASR criterion directly. In contrast to conventional methods, we incorporate array processing knowledge into the acoustic model. Moreover, we initialize the network with beamformers' coefficients. We investigate effects of such MC neural networks through ASR experiments on the real-world far-field data where users are interacting with an ASR system in uncontrolled acoustic environments. We show that our MC acoustic model can reduce a word error rate (WER) by~16.5\% compared to a single channel ASR system with the traditional log-mel filter bank energy (LFBE) feature on average. Our result also shows that our network with the spatial filtering layer on two-channel input achieves a relative WER reduction of~9.5\% compared to conventional beamforming with seven microphones.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.05299](http://arxiv.org/abs/1903.05299)

##### PDF
[http://arxiv.org/pdf/1903.05299](http://arxiv.org/pdf/1903.05299)

