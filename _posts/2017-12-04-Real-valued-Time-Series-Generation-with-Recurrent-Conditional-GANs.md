---
layout: post
title: "Real-valued Time Series Generation with Recurrent Conditional GANs"
date: 2017-12-04 04:31:38
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN RNN Classification Quantitative
author: Cristóbal Esteban, Stephanie L. Hyland, Gunnar Rätsch
mathjax: true
---

* content
{:toc}

##### Abstract
Generative Adversarial Networks (GANs) have shown remarkable success as a framework for training models to produce realistic-looking data. In this work, we propose a Recurrent GAN (RGAN) and Recurrent Conditional GAN (RCGAN) to produce realistic real-valued multi-dimensional time series, with an emphasis on their application to medical data. RGANs make use of recurrent neural networks in the generator and the discriminator. In the case of RCGANs, both of these RNNs are conditioned on auxiliary information. We demonstrate our models in a set of toy datasets, where we show visually and quantitatively (using sample likelihood and maximum mean discrepancy) that they can successfully generate realistic time-series. We also describe novel evaluation methods for GANs, where we generate a synthetic labelled training dataset, and evaluate on a real test set the performance of a model trained on the synthetic data, and vice-versa. We illustrate with these metrics that RCGANs can generate time-series data useful for supervised training, with only minor degradation in performance on real test data. This is demonstrated on digit classification from 'serialised' MNIST and by training an early warning system on a medical dataset of 17,000 patients from an intensive care unit. We further discuss and analyse the privacy concerns that may arise when using RCGANs to generate realistic synthetic medical time series data.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1706.02633](https://arxiv.org/abs/1706.02633)

##### PDF
[https://arxiv.org/pdf/1706.02633](https://arxiv.org/pdf/1706.02633)

