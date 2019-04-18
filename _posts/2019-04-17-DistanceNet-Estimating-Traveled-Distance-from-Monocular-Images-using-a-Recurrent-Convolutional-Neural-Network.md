---
layout: post
title: "DistanceNet: Estimating Traveled Distance from Monocular Images using a Recurrent Convolutional Neural Network"
date: 2019-04-17 06:38:00
categories: arXiv_CV
tags: arXiv_CV CNN RNN Deep_Learning Prediction SLAM
author: Robin Kreuzig, Matthias Ochs, Rudolf Mester
mathjax: true
---

* content
{:toc}

##### Abstract
Classical monocular vSLAM/VO methods suffer from the scale ambiguity problem. Hybrid approaches solve this problem by adding deep learning methods, for example by using depth maps which are predicted by a CNN. We suggest that it is better to base scale estimation on estimating the traveled distance for a set of subsequent images. In this paper, we propose a novel end-to-end many-to-one traveled distance estimator. By using a deep recurrent convolutional neural network (RCNN), the traveled distance between the first and last image of a set of consecutive frames is estimated by our DistanceNet. Geometric features are learned in the CNN part of our model, which are subsequently used by the RNN to learn dynamics and temporal information. Moreover, we exploit the natural order of distances by using ordinal regression to predict the distance. The evaluation on the KITTI dataset shows that our approach outperforms current state-of-the-art deep learning pose estimators and classical mono vSLAM/VO methods in terms of distance prediction. Thus, our DistanceNet can be used as a component to solve the scale problem and help improve current and future classical mono vSLAM/VO methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.08105](http://arxiv.org/abs/1904.08105)

##### PDF
[http://arxiv.org/pdf/1904.08105](http://arxiv.org/pdf/1904.08105)

