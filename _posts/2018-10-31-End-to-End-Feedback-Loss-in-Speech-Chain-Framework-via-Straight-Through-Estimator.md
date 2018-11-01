---
layout: post
title: "End-to-End Feedback Loss in Speech Chain Framework via Straight-Through Estimator"
date: 2018-10-31 05:05:37
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Recognition
author: Andros Tjandra, Sakriani Sakti, Satoshi Nakamura
mathjax: true
---

* content
{:toc}

##### Abstract
The speech chain mechanism integrates automatic speech recognition (ASR) and text-to-speech synthesis (TTS) modules into a single cycle during training. In our previous work, we applied a speech chain mechanism as a semi-supervised learning. It provides the ability for ASR and TTS to assist each other when they receive unpaired data and let them infer the missing pair and optimize the model with reconstruction loss. If we only have speech without transcription, ASR generates the most likely transcription from the speech data, and then TTS uses the generated transcription to reconstruct the original speech features. However, in previous papers, we just limited our back-propagation to the closest module, which is the TTS part. One reason is that back-propagating the error through the ASR is challenging due to the output of the ASR are discrete tokens, creating non-differentiability between the TTS and ASR. In this paper, we address this problem and describe how to thoroughly train a speech chain end-to-end for reconstruction loss using a straight-through estimator (ST). Experimental results revealed that, with sampling from ST-Gumbel-Softmax, we were able to update ASR parameters and improve the ASR performances by 11\% relative CER reduction compared to the baseline.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.13107](http://arxiv.org/abs/1810.13107)

##### PDF
[http://arxiv.org/pdf/1810.13107](http://arxiv.org/pdf/1810.13107)

