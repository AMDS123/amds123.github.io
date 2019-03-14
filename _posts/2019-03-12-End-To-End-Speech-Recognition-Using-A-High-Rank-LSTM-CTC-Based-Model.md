---
layout: post
title: "End-To-End Speech Recognition Using A High Rank LSTM-CTC Based Model"
date: 2019-03-12 23:40:27
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition RNN Classification Recognition
author: Yangyang Shi, Mei-Yuh Hwang, Xin Lei
mathjax: true
---

* content
{:toc}

##### Abstract
Long Short Term Memory Connectionist Temporal Classification (LSTM-CTC) based end-to-end models are widely used in speech recognition due to its simplicity in training and efficiency in decoding. In conventional LSTM-CTC based models, a bottleneck projection matrix maps the hidden feature vectors obtained from LSTM to softmax output layer. In this paper, we propose to use a high rank projection layer to replace the projection matrix. The output from the high rank projection layer is a weighted combination of vectors that are projected from the hidden feature vectors via different projection matrices and non-linear activation function. The high rank projection layer is able to improve the expressiveness of LSTM-CTC models. The experimental results show that on Wall Street Journal (WSJ) corpus and LibriSpeech data set, the proposed method achieves 4%-6% relative word error rate (WER) reduction over the baseline CTC system. They outperform other published CTC based end-to-end (E2E) models under the condition that no external data or data augmentation is applied. Code has been made available at https://github.com/mobvoi/lstm_ctc.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.05261](http://arxiv.org/abs/1903.05261)

##### PDF
[http://arxiv.org/pdf/1903.05261](http://arxiv.org/pdf/1903.05261)

