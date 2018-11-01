---
layout: post
title: "Exploring Speech Enhancement with Generative Adversarial Networks for Robust Speech Recognition"
date: 2018-10-31 00:48:59
categories: arXiv_SD
tags: arXiv_SD Adversarial GAN Speech_Recognition Recognition
author: Chris Donahue, Bo Li, Rohit Prabhavalkar
mathjax: true
---

* content
{:toc}

##### Abstract
We investigate the effectiveness of generative adversarial networks (GANs) for speech enhancement, in the context of improving noise robustness of automatic speech recognition (ASR) systems. Prior work demonstrates that GANs can effectively suppress additive noise in raw waveform speech signals, improving perceptual quality metrics; however this technique was not justified in the context of ASR. In this work, we conduct a detailed study to measure the effectiveness of GANs in enhancing speech contaminated by both additive and reverberant noise. Motivated by recent advances in image processing, we propose operating GANs on log-Mel filterbank spectra instead of waveforms, which requires less computation and is more robust to reverberant noise. While GAN enhancement improves the performance of a clean-trained ASR system on noisy speech, it falls short of the performance achieved by conventional multi-style training (MTR). By appending the GAN-enhanced features to the noisy inputs and retraining, we achieve a 7% WER improvement relative to the MTR system.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1711.05747](http://arxiv.org/abs/1711.05747)

##### PDF
[http://arxiv.org/pdf/1711.05747](http://arxiv.org/pdf/1711.05747)

