---
layout: post
title: "TAPAS: Train-less Accuracy Predictor for Architecture Search"
date: 2018-06-01 09:17:15
categories: arXiv_CV
tags: arXiv_CV NAS Reinforcement_Learning Classification Prediction
author: R. Istrate, F. Scheidegger, G. Mariani, D. Nikolopoulos, C. Bekas, A. C. I. Malossi
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years an increasing number of researchers and practitioners have been suggesting algorithms for large-scale neural network architecture search: genetic algorithms, reinforcement learning, learning curve extrapolation, and accuracy predictors. None of them, however, demonstrated high-performance without training new experiments in the presence of unseen datasets. We propose a new deep neural network accuracy predictor, that estimates in fractions of a second classification performance for unseen input datasets, without training. In contrast to previously proposed approaches, our prediction is not only calibrated on the topological network information, but also on the characterization of the dataset-difficulty which allows us to re-tune the prediction without any training. Our predictor achieves a performance which exceeds 100 networks per second on a single GPU, thus creating the opportunity to perform large-scale architecture search within a few minutes. We present results of two searches performed in 400 seconds on a single GPU. Our best discovered networks reach 93.67% accuracy for CIFAR-10 and 81.01% for CIFAR-100, verified by training. These networks are performance competitive with other automatically discovered state-of-the-art networks however we only needed a small fraction of the time to solution and computational resources.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1806.00250](https://arxiv.org/abs/1806.00250)

##### PDF
[https://arxiv.org/pdf/1806.00250](https://arxiv.org/pdf/1806.00250)

