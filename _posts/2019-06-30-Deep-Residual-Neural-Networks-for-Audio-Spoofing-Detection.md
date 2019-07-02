---
layout: post
title: "Deep Residual Neural Networks for Audio Spoofing Detection"
date: 2019-06-30 23:58:28
categories: arXiv_SD
tags: arXiv_SD CNN Classification Detection
author: Moustafa Alzantot, Ziqi Wang, Mani B. Srivastava
mathjax: true
---

* content
{:toc}

##### Abstract
The state-of-art models for speech synthesis and voice conversion are capable of generating synthetic speech that is perceptually indistinguishable from bonafide human speech. These methods represent a threat to the automatic speaker verification (ASV) systems. Additionally, replay attacks where the attacker uses a speaker to replay a previously recorded genuine human speech are also possible. We present our solution for the ASVSpoof2019 competition, which aims to develop countermeasure systems that distinguish between spoofing attacks and genuine speeches. Our model is inspired by the success of residual convolutional networks in many classification tasks. We build three variants of a residual convolutional neural network that accept different feature representations (MFCC, Log-magnitude STFT, and CQCC) of input. We compare the performance achieved by our model variants and the competition baseline models. In the logical access scenario, the fusion of our models has zero t-DCF cost and zero equal error rate (EER), as evaluated on the development set. On the evaluation set, our model fusion improves the t-DCF and EER by 25% compared to the baseline algorithms. Against physical access replay attacks, our model fusion improves the baseline algorithms t-DCF and EER scores by 71% and 75% on the evaluation set, respectively.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.00501](http://arxiv.org/abs/1907.00501)

##### PDF
[http://arxiv.org/pdf/1907.00501](http://arxiv.org/pdf/1907.00501)

