---
layout: post
title: "Noise Adaptive Speech Enhancement using Domain Adversarial Training"
date: 2019-07-01 09:02:16
categories: arXiv_SD
tags: arXiv_SD Adversarial
author: Chien-Feng Liao, Yu Tsao, Hung-Yi Lee, Hsin-Min Wang
mathjax: true
---

* content
{:toc}

##### Abstract
In this study, we propose a novel noise adaptive speech enhancement (SE) system, which employs a domain adversarial training (DAT) approach to tackle the issue of a noise type mismatch between the training and testing conditions. Such a mismatch is a critical problem in deep-learning-based SE systems. A large mismatch may cause a serious performance degradation to the SE performance. Because we generally use a well-trained SE system to handle various unseen noise types, a noise type mismatch commonly occurs in real-world scenarios. The proposed noise adaptive SE system contains an encoder-decoder-based enhancement model and a domain discriminator model. During adaptation, the DAT approach encourages the encoder to produce noise-invariant features based on the information from the discriminator model and consequentially increases the robustness of the enhancement model to unseen noise types. Herein, we regard stationary noises as the source domain (with the ground truth of clean speech) and non-stationary noises as the target domain (without the ground truth). We evaluated the proposed system on TIMIT sentences. The experiment results show that the proposed noise adaptive SE system successfully provides significant improvements in PESQ (19.0%), SSNR (39.3%), and STOI (27.0%) over the SE system without an adaptation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1807.07501](http://arxiv.org/abs/1807.07501)

##### PDF
[http://arxiv.org/pdf/1807.07501](http://arxiv.org/pdf/1807.07501)

