---
layout: post
title: "Training Auto-encoder-based Optimizers for Terahertz Image Reconstruction"
date: 2019-07-02 14:01:35
categories: arXiv_CV
tags: arXiv_CV Optimization Prediction
author: Tak Ming Wong, Matthias Kahl, Peter Haring Bol&#xed;var, Andreas Kolb, Michael M&#xf6;ller
mathjax: true
---

* content
{:toc}

##### Abstract
Terahertz (THz) sensing is a promising imaging technology for a wide variety of different applications. Extracting the interpretable and physically meaningful parameters for such applications, however, requires solving an inverse problem in which a model function determined by these parameters needs to be fitted to the measured data. Since the underlying optimization problem is nonconvex and very costly to solve, we propose learning the prediction of suitable parameters from the measured data directly. More precisely, we develop a model-based autoencoder in which the encoder network predicts suitable parameters and the decoder is fixed to a physically meaningful model function, such that we can train the encoding network in an unsupervised way. We illustrate numerically that the resulting network is more than 140 times faster than classical optimization techniques while making predictions with only slightly higher objective values. Using such predictions as starting points of local optimization techniques allows us to converge to better local minima about twice as fast as optimization without the network-based initialization.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.01377](http://arxiv.org/abs/1907.01377)

##### PDF
[http://arxiv.org/pdf/1907.01377](http://arxiv.org/pdf/1907.01377)

