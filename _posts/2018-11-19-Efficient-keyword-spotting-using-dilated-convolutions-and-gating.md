---
layout: post
title: "Efficient keyword spotting using dilated convolutions and gating"
date: 2018-11-19 13:51:10
categories: arXiv_CL
tags: arXiv_CL RNN Detection
author: Alice Coucke, Mohammed Chlieh, Thibault Gisselbrecht, David Leroy, Mathieu Poumeyrol, Thibaut Lavril
mathjax: true
---

* content
{:toc}

##### Abstract
We explore the application of end-to-end stateless temporal modeling to small-footprint keyword spotting as opposed to recurrent networks that model long-term temporal dependencies using internal states. We propose a model inspired by the recent success of dilated convolutions in sequence modeling applications, allowing to train deeper architectures in resource-constrained configurations. Gated activations and residual connections are also added, following a similar configuration to WaveNet. In addition, we apply a custom target labeling that back-propagates loss from specific frames of interest, therefore yielding higher accuracy and only requiring to detect the end of the keyword. Our experimental results show that our model outperforms a max-pooling loss trained recurrent neural network using LSTM cells, with a significant decrease in false rejection rate. The underlying dataset - "Hey Snips" utterances recorded by over 2.2K different speakers - has been made publicly available to establish an open reference for wake-word detection.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.07684](http://arxiv.org/abs/1811.07684)

##### PDF
[http://arxiv.org/pdf/1811.07684](http://arxiv.org/pdf/1811.07684)

