---
layout: post
title: "Calibration of Encoder Decoder Models for Neural Machine Translation"
date: 2019-03-03 01:08:47
categories: arXiv_CL
tags: arXiv_CL Attention NMT Inference Prediction
author: Aviral Kumar, Sunita Sarawagi
mathjax: true
---

* content
{:toc}

##### Abstract
We study the calibration of several state of the art neural machine translation(NMT) systems built on attention-based encoder-decoder models. For structured outputs like in NMT, calibration is important not just for reliable confidence with predictions, but also for proper functioning of beam-search inference. We show that most modern NMT models are surprisingly miscalibrated even when conditioned on the true previous tokens. Our investigation leads to two main reasons -- severe miscalibration of EOS (end of sequence marker) and suppression of attention uncertainty. We design recalibration methods based on these signals and demonstrate improved accuracy, better sequence-level calibration, and more intuitive results from beam-search.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1903.00802](https://arxiv.org/abs/1903.00802)

##### PDF
[https://arxiv.org/pdf/1903.00802](https://arxiv.org/pdf/1903.00802)

