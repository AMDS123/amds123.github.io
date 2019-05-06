---
layout: post
title: "LSTM: A Search Space Odyssey"
date: 2017-10-04 11:40:31
categories: arXiv_CV
tags: arXiv_CV Speech_Recognition RNN Recognition
author: Klaus Greff, Rupesh Kumar Srivastava, Jan Koutník, Bas R. Steunebrink, Jürgen Schmidhuber
mathjax: true
---

* content
{:toc}

##### Abstract
Several variants of the Long Short-Term Memory (LSTM) architecture for recurrent neural networks have been proposed since its inception in 1995. In recent years, these networks have become the state-of-the-art models for a variety of machine learning problems. This has led to a renewed interest in understanding the role and utility of various computational components of typical LSTM variants. In this paper, we present the first large-scale analysis of eight LSTM variants on three representative tasks: speech recognition, handwriting recognition, and polyphonic music modeling. The hyperparameters of all LSTM variants for each task were optimized separately using random search, and their importance was assessed using the powerful fANOVA framework. In total, we summarize the results of 5400 experimental runs ($\approx 15$ years of CPU time), which makes our study the largest of its kind on LSTM networks. Our results show that none of the variants can improve upon the standard LSTM architecture significantly, and demonstrate the forget gate and the output activation function to be its most critical components. We further observe that the studied hyperparameters are virtually independent and derive guidelines for their efficient adjustment.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1503.04069](https://arxiv.org/abs/1503.04069)

##### PDF
[https://arxiv.org/pdf/1503.04069](https://arxiv.org/pdf/1503.04069)

