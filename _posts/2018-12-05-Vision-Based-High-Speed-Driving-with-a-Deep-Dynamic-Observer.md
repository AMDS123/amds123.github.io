---
layout: post
title: "Vision-Based High Speed Driving with a Deep Dynamic Observer"
date: 2018-12-05 16:07:24
categories: arXiv_RO
tags: arXiv_RO CNN RNN Deep_Learning Detection
author: Paul Drews, Grady Williams, Brian Goldfain, Evangelos A. Theodorou, James M. Rehg
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we present a framework for combining deep learning-based road detection, particle filters, and Model Predictive Control (MPC) to drive aggressively using only a monocular camera, IMU, and wheel speed sensors. This framework uses deep convolutional neural networks combined with LSTMs to learn a local cost map representation of the track in front of the vehicle. A particle filter uses this dynamic observation model to localize in a schematic map, and MPC is used to drive aggressively using this particle filter based state estimate. We show extensive real world testing results, and demonstrate reliable operation of the vehicle at the friction limits on a complex dirt track. We reach speeds above 27 mph (12 m/s) on a dirt track with a 105 foot (32m) long straight using our 1:5 scale test vehicle.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.02071](http://arxiv.org/abs/1812.02071)

##### PDF
[http://arxiv.org/pdf/1812.02071](http://arxiv.org/pdf/1812.02071)

