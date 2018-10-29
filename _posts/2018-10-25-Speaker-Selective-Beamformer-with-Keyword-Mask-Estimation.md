---
layout: post
title: "Speaker Selective Beamformer with Keyword Mask Estimation"
date: 2018-10-25 05:45:06
categories: arXiv_SD
tags: arXiv_SD Speech_Recognition Recognition
author: Yusuke Kida, Dung Tran, Motoi Omachi, Toru Taniguchi, Yuya Fujita
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the problem of automatic speech recognition (ASR) of a target speaker in background speech. The novelty of our approach is that we focus on a wakeup keyword, which is usually used for activating ASR systems like smart speakers. The proposed method firstly utilizes a DNN-based mask estimator to separate the mixture signal into the keyword signal uttered by the target speaker and the remaining background speech. Then the separated signals are used for calculating a beamforming filter to enhance the subsequent utterances from the target speaker. Experimental evaluations show that the trained DNN-based mask can selectively separate the keyword and background speech from the mixture signal. The effectiveness of the proposed method is also verified with Japanese ASR experiments, and we confirm that the character error rates are significantly improved by the proposed method for both simulated and real recorded test sets.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.10727](https://arxiv.org/abs/1810.10727)

##### PDF
[https://arxiv.org/pdf/1810.10727](https://arxiv.org/pdf/1810.10727)

