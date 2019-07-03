---
layout: post
title: "A Fully Time-domain Neural Model for Subband-based Speech Synthesizer"
date: 2019-07-02 00:19:38
categories: arXiv_SD
tags: arXiv_SD CNN
author: Azam Rabiee, Geonmin Kim, Tae-Ho Kim, Soo-Young Lee
mathjax: true
---

* content
{:toc}

##### Abstract
This paper introduces a deep neural network model for subband-based speech synthesizer. The model benefits from the short bandwidth of the subband signals to reduce the complexity of the time-domain speech generator. We employed the multi-level wavelet analysis/synthesis to decompose/reconstruct the signal into subbands in time domain. Inspired from the WaveNet, a convolutional neural network (CNN) model predicts subband speech signals fully in time domain. Due to the short bandwidth of the subbands, a simple network architecture is enough to train the simple patterns of the subbands accurately. In the ground truth experiments with teacher-forcing, the subband synthesizer outperforms the fullband model significantly in terms of both subjective and objective measures. In addition, by conditioning the model on the phoneme sequence using a pronunciation dictionary, we have achieved the fully time-domain neural model for subband-based text-to-speech (TTS) synthesizer, which is nearly end-to-end. The generated speech of the subband TTS shows comparable quality as the fullband one with a slighter network architecture for each subband.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.05319](http://arxiv.org/abs/1810.05319)

##### PDF
[http://arxiv.org/pdf/1810.05319](http://arxiv.org/pdf/1810.05319)

