---
layout: post
title: "A High-Performance CNN Method for Offline Handwritten Chinese Character Recognition and Visualization"
date: 2019-05-28 07:33:45
categories: arXiv_CV
tags: arXiv_CV CNN Recognition
author: Pavlo Melnyk, Zhiqiang You, Keqin Li
mathjax: true
---

* content
{:toc}

##### Abstract
Recent researches introduced fast, compact and efficient convolutional neural networks (CNNs) for offline handwritten Chinese character recognition (HCCR). However, many of them did not address the problem of network interpretability. We propose a new architecture of a deep CNN with high recognition performance which is capable of learning deep features for visualization. A special characteristic of our model is the bottleneck layers which enable us to retain its expressiveness while reducing the number of multiply-accumulate operations and the required storage. We introduce a modification of global weighted average pooling (GWAP) - global weighted output average pooling (GWOAP). This paper demonstrates how they allow us to calculate class activation maps (CAMs) in order to indicate the most relevant input character image regions used by our CNN to identify a certain class. Evaluating on the ICDAR-2013 offline HCCR competition dataset, we show that our model enables a relative 0.83% error reduction while having 49% fewer parameters and the same computational cost compared to the current state-of-the-art single-network method trained only on handwritten data. Our solution outperforms even recent residual learning approaches.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.11489](http://arxiv.org/abs/1812.11489)

##### PDF
[http://arxiv.org/pdf/1812.11489](http://arxiv.org/pdf/1812.11489)

