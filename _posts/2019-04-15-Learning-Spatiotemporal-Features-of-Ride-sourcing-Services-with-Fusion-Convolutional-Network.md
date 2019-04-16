---
layout: post
title: "Learning Spatiotemporal Features of Ride-sourcing Services with Fusion Convolutional Network"
date: 2019-04-15 03:10:45
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning
author: Dapeng Zhang, Feng Xiao, Lu Li, Gang Kou
mathjax: true
---

* content
{:toc}

##### Abstract
In order to collectively forecast the demand of ride-sourcing services in all regions of a city, convolutional neural networks (CNNs) have been applied with commendable results. However, local statistical differences throughout the geographical layout of the city make the spatial stationarity assumption of the convolution invalid, which limits the performance of CNNs on demand forecasting task. Hence, we propose a novel deep learning framework called LC-ST-FCN (locally-connected spatiotemporal fully-convolutional neural network) that consists of a stack of 3D convolutional layers, 2D (standard) convolutional layers, and locally connected convolutional layers. This fully convolutional architecture maintains the spatial coordinates of the input and no spatial information is lost between layers. Features are fused across layers to define a tunable nonlinear local-to-global-to-local representation, where both global and local statistics can be learned to improve predictive performance. Furthermore, as the local statistics vary from region to region, the arithmetic-mean-based metrics frequently used in spatial stationarity situations cannot effectively evaluate the models. We propose a weighted-arithmetic approach to deal with this situation. In the experiments, a real dataset from a ride-sourcing service platform (DiDiChuxing) is used, which demonstrates the effectiveness and superiority of our proposed model and evaluation method.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.06823](http://arxiv.org/abs/1904.06823)

##### PDF
[http://arxiv.org/pdf/1904.06823](http://arxiv.org/pdf/1904.06823)

