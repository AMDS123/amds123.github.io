---
layout: post
title: "Multi-scale aggregation of phase information for reducing computational cost of CNN based DOA estimation"
date: 2018-11-20 12:29:51
categories: arXiv_SD
tags: arXiv_SD CNN Relation
author: Soumitro Chakrabarty, Emanu&#xeb;l A. P. Habets
mathjax: true
---

* content
{:toc}

##### Abstract
In a recent work on direction-of-arrival (DOA) estimation of multiple speakers with convolutional neural networks (CNNs), the phase component of short-time Fourier transform (STFT) coefficients of the microphone signal is given as input and small filters are used to learn the phase relations between neighboring microphones. Due to this chosen filter size, $M-1$ convolution layers are required to achieve the best performance for a microphone array with M microphones. For arrays with large number of microphones, this requirement leads to a high computational cost making the method practically infeasible. In this work, we propose to use systematic dilations of the convolution filters in each of the convolution layers of the previously proposed CNN for expansion of the receptive field of the filters to reduce the computational cost of the method. Different strategies for expansion of the receptive field of the filters for a specific microphone array are explored. With experimental analysis of the different strategies, it is shown that an aggressive expansion strategy results in a considerable reduction in computational cost while a relatively gradual expansion of the receptive field exhibits the best DOA estimation performance along with reduction in the computational cost.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.08552](http://arxiv.org/abs/1811.08552)

##### PDF
[http://arxiv.org/pdf/1811.08552](http://arxiv.org/pdf/1811.08552)

