---
layout: post
title: "Multi-resolution neural networks for tracking seismic horizons from few training images"
date: 2018-12-26 07:35:24
categories: arXiv_CV
tags: arXiv_CV Tracking CNN Classification Prediction
author: Bas Peters, Justin Granek, Eldad Haber
mathjax: true
---

* content
{:toc}

##### Abstract
Detecting a specific horizon in seismic images is a valuable tool for geological interpretation. Because hand-picking the locations of the horizon is a time-consuming process, automated computational methods were developed starting three decades ago. Older techniques for such picking include interpolation of control points however, in recent years neural networks have been used for this task. Until now, most networks trained on small patches from larger images. This limits the networks ability to learn from large-scale geologic structures. Moreover, currently available networks and training strategies require label patches that have full and continuous annotations, which are also time-consuming to generate. 
 We propose a projected loss-function for training convolutional networks with a multi-resolution structure, including variants of the U-net. Our networks learn from a small number of large seismic images without creating patches. The projected loss-function enables training on labels with just a few annotated pixels and has no issue with the other unknown label pixels. Training uses all data without reserving some for validation. Only the labels are split into training/testing. Contrary to other work on horizon tracking, we train the network to perform non-linear regression, and not classification. As such, we propose labels as the convolution of a Gaussian kernel and the known horizon locations that indicate uncertainty in the labels. The network output is the probability of the horizon location. We demonstrate the proposed computational ingredients on two different datasets, for horizon extrapolation and interpolation. We show that the predictions of our methodology are accurate even in areas far from known horizon locations because our learning strategy exploits all data in large seismic images.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.11092](http://arxiv.org/abs/1812.11092)

##### PDF
[http://arxiv.org/pdf/1812.11092](http://arxiv.org/pdf/1812.11092)

