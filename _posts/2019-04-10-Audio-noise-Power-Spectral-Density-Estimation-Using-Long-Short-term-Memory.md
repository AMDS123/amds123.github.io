---
layout: post
title: "Audio-noise Power Spectral Density Estimation Using Long Short-term Memory"
date: 2019-04-10 13:14:11
categories: arXiv_SD
tags: arXiv_SD RNN
author: Xiaofei Li, Simon Leglaive, Laurent Girin, Radu Horaud
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a method using a long short-term memory (LSTM) network to estimate the noise power spectral density (PSD) of single-channel audio signals represented in the short time Fourier transform (STFT) domain. An LSTM network common to all frequency bands is trained, which processes each frequency band individually by mapping the noisy STFT magnitude sequence to its corresponding noise PSD sequence. Unlike deep-learning-based speech enhancement methods that learn the full-band spectral structure of speech segments, the proposed method exploits the sub-band STFT magnitude evolution of noise with a long time dependency, in the spirit of the unsupervised noise estimators described in the literature. Speaker- and speech-independent experiments with different types of noise show that the proposed method outperforms the unsupervised estimators, and generalizes well to noise types that are not present in the training set.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.05166](http://arxiv.org/abs/1904.05166)

##### PDF
[http://arxiv.org/pdf/1904.05166](http://arxiv.org/pdf/1904.05166)

