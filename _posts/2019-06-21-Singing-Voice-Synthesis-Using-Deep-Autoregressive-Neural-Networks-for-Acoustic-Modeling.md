---
layout: post
title: "Singing Voice Synthesis Using Deep Autoregressive Neural Networks for Acoustic Modeling"
date: 2019-06-21 06:40:06
categories: arXiv_SD
tags: arXiv_SD Attention RNN
author: Yuan-Hao Yi, Yang Ai, Zhen-Hua Ling, Li-Rong Dai
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a method of using autoregressive neural networks for the acoustic modeling of singing voice synthesis (SVS). Singing voice differs from speech and it contains more local dynamic movements of acoustic features, e.g., vibratos. Therefore, our method adopts deep autoregressive (DAR) models to predict the F0 and spectral features of singing voice in order to better describe the dependencies among the acoustic features of consecutive frames. For F0 modeling, discretized F0 values are used and the influences of the history length in DAR are analyzed by experiments. An F0 post-processing strategy is also designed to alleviate the inconsistency between the predicted F0 contours and the F0 values determined by music notes. Furthermore, we extend the DAR model to deal with continuous spectral features, and a prenet module with self-attention layers is introduced to process historical frames. Experiments on a Chinese singing voice corpus demonstrate that our method using DARs can produce F0 contours with vibratos effectively, and can achieve better objective and subjective performance than the conventional method using recurrent neural networks (RNNs).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.08977](http://arxiv.org/abs/1906.08977)

##### PDF
[http://arxiv.org/pdf/1906.08977](http://arxiv.org/pdf/1906.08977)

