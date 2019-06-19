---
layout: post
title: "Boosting CNN beyond Label in Inverse Problems"
date: 2019-06-18 01:21:40
categories: arXiv_CV
tags: arXiv_CV CNN Prediction
author: Eunju Cha, Jaeduck Jang, Junho Lee, Eunha Lee, Jong Chul Ye
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks (CNN) have been extensively used for inverse problems. However, their prediction error for unseen test data is difficult to estimate a priori since the neural networks are trained using only selected data and their architecture are largely considered a blackbox. This poses a fundamental challenge to neural networks for unsupervised learning or improvement beyond the label. In this paper, we show that the recent unsupervised learning methods such as Noise2Noise, Stein's unbiased risk estimator (SURE)-based denoiser, and Noise2Void are closely related to each other in their formulation of an unbiased estimator of the prediction error, but each of them are associated with its own limitations. Based on these observations, we provide a novel boosting estimator for the prediction error. In particular, by employing combinatorial convolutional frame representation of encoder-decoder CNN and synergistically combining it with the batch normalization, we provide a close form formulation for the unbiased estimator of the prediction error that can be minimized for neural network training beyond the label. Experimental results show that the resulting algorithm, what we call Noise2Boosting, provides consistent improvement in various inverse problems under both supervised and unsupervised learning setting.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.07330](http://arxiv.org/abs/1906.07330)

##### PDF
[http://arxiv.org/pdf/1906.07330](http://arxiv.org/pdf/1906.07330)

