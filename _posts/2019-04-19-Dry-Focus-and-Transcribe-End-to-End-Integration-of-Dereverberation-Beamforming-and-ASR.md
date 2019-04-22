---
layout: post
title: "Dry, Focus, and Transcribe: End-to-End Integration of Dereverberation, Beamforming, and ASR"
date: 2019-04-19 01:36:37
categories: arXiv_CL
tags: arXiv_CL Knowledge Speech_Recognition Recognition
author: Aswin Shanmugam Subramanian, Xiaofei Wang, Shinji Watanabe, Toru Taniguchi, Dung Tran, Yuya Fujita
mathjax: true
---

* content
{:toc}

##### Abstract
Sequence-to-sequence (S2S) modeling is becoming a popular paradigm for automatic speech recognition (ASR) because of its ability to jointly optimize all the conventional ASR components in an end-to-end (E2E) fashion. This paper extends the ability of E2E ASR from standard close-talk to far-field applications by encompassing entire multichannel speech enhancement and ASR components within the S2S model. There have been previous studies on jointly optimizing neural beamforming alongside E2E ASR for denoising. It is clear from both recent challenge outcomes and successful products that far-field systems would be incomplete without solving both denoising and dereverberation simultaneously. This paper proposes a novel architecture for far-field ASR by composing neural extensions of dereverberation and beamforming modules with the S2S ASR module as a single differentiable neural network and also clearly defining the role of each subnetwork. To our knowledge, this is the first successful demonstration of such a system, which we term DFTnet (dry, focus, and transcribe). It achieves better performance than conventional pipeline methods on the DIRHA English dataset and comparable performance on the REVERB dataset. It also has additional advantages of being neither iterative nor requiring parallel noisy and clean speech data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.09049](http://arxiv.org/abs/1904.09049)

##### PDF
[http://arxiv.org/pdf/1904.09049](http://arxiv.org/pdf/1904.09049)

