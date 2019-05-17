---
layout: post
title: "Predicting Future Lane Changes of Other Highway Vehicles using RNN-based Deep Models"
date: 2019-05-16 16:56:16
categories: arXiv_RO
tags: arXiv_RO RNN Prediction
author: Sajan Patel, Brent Griffin, Kristofer Kusano, Jason J. Corso
mathjax: true
---

* content
{:toc}

##### Abstract
In the event of sensor failure, autonomous vehicles need to safely execute emergency maneuvers while avoiding other vehicles on the road. To accomplish this, the sensor-failed vehicle must predict the future semantic behaviors of other drivers, such as lane changes, as well as their future trajectories given a recent window of past sensor observations. We address the first issue of semantic behavior prediction in this paper, which is a precursor to trajectory prediction, by introducing a framework that leverages the power of recurrent neural networks (RNNs) and graphical models. Our goal is to predict the future categorical driving intent, for lane changes, of neighboring vehicles up to three seconds into the future given as little as a one-second window of past LIDAR, GPS, inertial, and map data. 
 We collect real-world data containing over 20 hours of highway driving using an autonomous Toyota vehicle. We propose a composite RNN model by adopting the methodology of Structural Recurrent Neural Networks (RNNs) to learn factor functions and take advantage of both the high-level structure of graphical models and the sequence modeling power of RNNs, which we expect to afford more transparent modeling and activity than opaque, single RNN models. To demonstrate our approach, we validate our model using authentic interstate highway driving to predict the future lane change maneuvers of other vehicles neighboring our autonomous vehicle. We find that our composite Structural RNN outperforms baselines by as much as 12% in balanced accuracy metrics.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1801.04340](http://arxiv.org/abs/1801.04340)

##### PDF
[http://arxiv.org/pdf/1801.04340](http://arxiv.org/pdf/1801.04340)

