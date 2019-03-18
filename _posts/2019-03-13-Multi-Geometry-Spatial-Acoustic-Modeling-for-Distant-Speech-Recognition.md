---
layout: post
title: "Multi-Geometry Spatial Acoustic Modeling for Distant Speech Recognition"
date: 2019-03-13 03:32:53
categories: arXiv_SD
tags: arXiv_SD Speech_Recognition Optimization RNN Recognition
author: Kenichi Kumatani, Wu Minhua, Shiva Sundaram, Nikko Strom, Bjorn Hoffmeister
mathjax: true
---

* content
{:toc}

##### Abstract
The use of spatial information with multiple microphones can improve far-field automatic speech recognition (ASR) accuracy. However, conventional microphone array techniques degrade speech enhancement performance when there is an array geometry mismatch between design and test conditions. Moreover, such speech enhancement techniques do not always yield ASR accuracy improvement due to the difference between speech enhancement and ASR optimization objectives. In this work, we propose to unify an acoustic model framework by optimizing spatial filtering and long short-term memory (LSTM) layers from multi-channel (MC) input. Our acoustic model subsumes beamformers with multiple types of array geometry. In contrast to deep clustering methods that treat a neural network as a black box tool, the network encoding the spatial filters can process streaming audio data in real time without the accumulation of target signal statistics. We demonstrate the effectiveness of such MC neural networks through ASR experiments on the real-world far-field data. We show that our two-channel acoustic model can on average reduce word error rates (WERs) by~13.4 and~12.7% compared to a single channel ASR system with the log-mel filter bank energy (LFBE) feature under the matched and mismatched microphone placement conditions, respectively. Our result also shows that our two-channel network achieves a relative WER reduction of over~7.0% compared to conventional beamforming with seven microphones overall.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.06539](http://arxiv.org/abs/1903.06539)

##### PDF
[http://arxiv.org/pdf/1903.06539](http://arxiv.org/pdf/1903.06539)

