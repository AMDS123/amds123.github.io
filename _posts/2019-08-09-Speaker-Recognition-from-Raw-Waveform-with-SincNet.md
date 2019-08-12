---
layout: post
title: "Speaker Recognition from Raw Waveform with SincNet"
date: 2019-08-09 15:52:10
categories: arXiv_SD
tags: arXiv_SD CNN Deep_Learning Recognition
author: Mirco Ravanelli, Yoshua Bengio
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning is progressively gaining popularity as a viable alternative to i-vectors for speaker recognition. Promising results have been recently obtained with Convolutional Neural Networks (CNNs) when fed by raw speech samples directly. Rather than employing standard hand-crafted features, the latter CNNs learn low-level speech representations from waveforms, potentially allowing the network to better capture important narrow-band speaker characteristics such as pitch and formants. Proper design of the neural network is crucial to achieve this goal. This paper proposes a novel CNN architecture, called SincNet, that encourages the first convolutional layer to discover more meaningful filters. SincNet is based on parametrized sinc functions, which implement band-pass filters. In contrast to standard CNNs, that learn all elements of each filter, only low and high cutoff frequencies are directly learned from data with the proposed method. This offers a very compact and efficient way to derive a customized filter bank specifically tuned for the desired application. Our experiments, conducted on both speaker identification and speaker verification tasks, show that the proposed architecture converges faster and performs better than a standard CNN on raw waveforms.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1808.00158](http://arxiv.org/abs/1808.00158)

##### PDF
[http://arxiv.org/pdf/1808.00158](http://arxiv.org/pdf/1808.00158)

