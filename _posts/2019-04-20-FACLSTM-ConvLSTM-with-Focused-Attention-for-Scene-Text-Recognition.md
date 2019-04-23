---
layout: post
title: "FACLSTM: ConvLSTM with Focused Attention for Scene Text Recognition"
date: 2019-04-20 05:44:37
categories: arXiv_CV
tags: arXiv_CV Attention CNN RNN Prediction Relation Recognition
author: Qingqing Wang, Wenjing Jia, Xiangjian He, Yue Lu, Michael Blumenstein, Ye Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Scene text recognition has recently been widely treated as a sequence-to-sequence prediction problem, where traditional fully-connected-LSTM (FC-LSTM) has played a critical role. Due to the limitation of FC-LSTM, existing methods have to convert 2-D feature maps into 1-D sequential feature vectors, resulting in severe damages of the valuable spatial and structural information of text images. In this paper, we argue that scene text recognition is essentially a spatiotemporal prediction problem for its 2-D image inputs, and propose a convolution LSTM (ConvLSTM)-based scene text recognizer, namely, FACLSTM, i.e., Focused Attention ConvLSTM, where the spatial correlation of pixels is fully leveraged when performing sequential prediction with LSTM. Particularly, the attention mechanism is properly incorporated into an efficient ConvLSTM structure via the convolutional operations and additional character center masks are generated to help focus attention on right feature areas. The experimental results on benchmark datasets IIIT5K, SVT and CUTE demonstrate that our proposed FACLSTM performs competitively on the regular, low-resolution and noisy text images, and outperforms the state-of-the-art approaches on the curved text with large margins.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.09405](http://arxiv.org/abs/1904.09405)

##### PDF
[http://arxiv.org/pdf/1904.09405](http://arxiv.org/pdf/1904.09405)

