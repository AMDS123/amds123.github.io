---
layout: post
title: "Differentiable Consistency Constraints for Improved Deep Speech Enhancement"
date: 2018-11-20 22:44:12
categories: arXiv_SD
tags: arXiv_SD Recognition
author: Scott Wisdom, John R. Hershey, Kevin Wilson, Jeremy Thorpe, Michael Chinen, Brian Patton, Rif A. Saurous
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, deep networks have led to dramatic improvements in speech enhancement by framing it as a data-driven pattern recognition problem. In many modern enhancement systems, large amounts of data are used to train a deep network to estimate masks for complex-valued short-time Fourier transforms (STFTs) to suppress noise and preserve speech. However, current masking approaches often neglect two important constraints: STFT consistency and mixture consistency. Without STFT consistency, the system's output is not necessarily the STFT of a time-domain signal, and without mixture consistency, the sum of the estimated sources does not necessarily equal the input mixture. Furthermore, the only previous approaches that apply mixture consistency use real-valued masks; mixture consistency has been ignored for complex-valued masks. In this paper, we show that STFT consistency and mixture consistency can be jointly imposed by adding simple differentiable projection layers to the enhancement network. These layers are compatible with real or complex-valued masks. Using both of these constraints with complex-valued masks provides a 0.7 dB increase in scale-invariant signal-to-distortion ratio (SI-SDR) on a large dataset of speech corrupted by a wide variety of nonstationary noise across a range of input SNRs.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.08521](http://arxiv.org/abs/1811.08521)

##### PDF
[http://arxiv.org/pdf/1811.08521](http://arxiv.org/pdf/1811.08521)

