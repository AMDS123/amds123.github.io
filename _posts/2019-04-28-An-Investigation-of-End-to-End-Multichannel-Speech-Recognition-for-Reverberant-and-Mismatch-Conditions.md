---
layout: post
title: "An Investigation of End-to-End Multichannel Speech Recognition for Reverberant and Mismatch Conditions"
date: 2019-04-28 06:13:42
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Recognition
author: Aswin Shanmugam Subramanian, Xiaofei Wang, Shinji Watanabe, Toru Taniguchi, Dung Tran, Yuya Fujita
mathjax: true
---

* content
{:toc}

##### Abstract
Sequence-to-sequence (S2S) modeling is becoming a popular paradigm for automatic speech recognition (ASR) because of its ability to jointly optimize all the conventional ASR components in an end-to-end (E2E) fashion. This report investigates the ability of E2E ASR from standard close-talk to far-field applications by encompassing entire multichannel speech enhancement and ASR components within the S2S model. There have been previous studies on jointly optimizing neural beamforming alongside E2E ASR for denoising. It is clear from both recent challenge outcomes and successful products that far-field systems would be incomplete without solving both denoising and dereverberation simultaneously. This report uses a recently developed architecture for far-field ASR by composing neural extensions of dereverberation and beamforming modules with the S2S ASR module as a single differentiable neural network and also clearly defining the role of each subnetwork. The original implementation of this architecture was successfully applied to the noisy speech recognition task (CHiME-4), while we applied this implementation to noisy reverberant tasks (DIRHA and REVERB). Our investigation shows that the method achieves better performance than conventional pipeline methods on the DIRHA English dataset and comparable performance on the REVERB dataset. It also has additional advantages of being neither iterative nor requiring parallel noisy and clean speech data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.09049](http://arxiv.org/abs/1904.09049)

##### PDF
[http://arxiv.org/pdf/1904.09049](http://arxiv.org/pdf/1904.09049)

