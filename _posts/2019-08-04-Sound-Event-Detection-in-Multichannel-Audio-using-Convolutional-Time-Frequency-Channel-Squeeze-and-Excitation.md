---
layout: post
title: "Sound Event Detection in Multichannel Audio using Convolutional Time-Frequency-Channel Squeeze and Excitation"
date: 2019-08-04 20:58:52
categories: arXiv_SD
tags: arXiv_SD Attention Embedding CNN RNN Detection
author: Wei Xia, Kazuhito Koishida
mathjax: true
---

* content
{:toc}

##### Abstract
In this study, we introduce a convolutional time-frequency-channel "Squeeze and Excitation" (tfc-SE) module to explicitly model inter-dependencies between the time-frequency domain and multiple channels. The tfc-SE module consists of two parts: tf-SE block and c-SE block which are designed to provide attention on time-frequency and channel domain, respectively, for adaptively recalibrating the input feature map. The proposed tfc-SE module, together with a popular Convolutional Recurrent Neural Network (CRNN) model, are evaluated on a multi-channel sound event detection task with overlapping audio sources: the training and test data are synthesized TUT Sound Events 2018 datasets, recorded with microphone arrays. We show that the tfc-SE module can be incorporated into the CRNN model at a small additional computational cost and bring significant improvements on sound event detection accuracy. We also perform detailed ablation studies by analyzing various factors that may influence the performance of the SE blocks. We show that with the best tfc-SE block, error rate (ER) decreases from 0.2538 to 0.2026, relative 20.17\% reduction of ER, and 5.72\% improvement of F1 score. The results indicate that the learned acoustic embeddings with the tfc-SE module efficiently strengthen time-frequency and channel-wise feature representations to improve the discriminative performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.01399](http://arxiv.org/abs/1908.01399)

##### PDF
[http://arxiv.org/pdf/1908.01399](http://arxiv.org/pdf/1908.01399)

