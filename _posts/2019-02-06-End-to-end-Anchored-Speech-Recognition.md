---
layout: post
title: "End-to-end Anchored Speech Recognition"
date: 2019-02-06 19:50:23
categories: arXiv_CL
tags: arXiv_CL Attention Face Speech_Recognition Recognition
author: Yiming Wang, Xing Fan, I-Fan Chen, Yuzong Liu, Tongfei Chen, Bj&#xf6;rn Hoffmeister
mathjax: true
---

* content
{:toc}

##### Abstract
Voice-controlled house-hold devices, like Amazon Echo or Google Home, face the problem of performing speech recognition of device-directed speech in the presence of interfering background speech, i.e., background noise and interfering speech from another person or media device in proximity need to be ignored. We propose two end-to-end models to tackle this problem with information extracted from the "anchored segment". The anchored segment refers to the wake-up word part of an audio stream, which contains valuable speaker information that can be used to suppress interfering speech and background noise. The first method is called "Multi-source Attention" where the attention mechanism takes both the speaker information and decoder state into consideration. The second method directly learns a frame-level mask on top of the encoder output. We also explore a multi-task learning setup where we use the ground truth of the mask to guide the learner. Given that audio data with interfering speech is rare in our training data set, we also propose a way to synthesize "noisy" speech from "clean" speech to mitigate the mismatch between training and test data. Our proposed methods show up to 15% relative reduction in WER for Amazon Alexa live data with interfering background speech without significantly degrading on clean speech.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.02383](http://arxiv.org/abs/1902.02383)

##### PDF
[http://arxiv.org/pdf/1902.02383](http://arxiv.org/pdf/1902.02383)

