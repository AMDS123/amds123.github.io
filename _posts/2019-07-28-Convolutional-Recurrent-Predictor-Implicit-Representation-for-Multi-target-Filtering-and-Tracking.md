---
layout: post
title: "Convolutional Recurrent Predictor: Implicit Representation for Multi-target Filtering and Tracking"
date: 2019-07-28 14:29:53
categories: arXiv_CV
tags: arXiv_CV Object_Detection Tracking CNN Object_Tracking RNN Prediction Detection
author: Mehryar Emambakhsh, Alessandro Bay, Eduard Vazquez
mathjax: true
---

* content
{:toc}

##### Abstract
Defining a multi-target motion model, which is an important step of tracking algorithms, can be very challenging. Using fixed models (as in several generative Bayesian algorithms, such as Kalman filters) can fail to accurately predict sophisticated target motions. On the other hand, sequential learning of the motion model (for example, using recurrent neural networks) can be computationally complex and difficult due to the variable unknown number of targets. In this paper, we propose a multi-target filtering and tracking algorithm which learns the motion model, simultaneously for all targets, from an implicitly represented state map and performs spatio-temporal data prediction. To this end, the multi-target state is modelled over a continuous hypothetical target space, using random finite sets and Gaussian mixture probability hypothesis density formulations. The prediction step is recursively performed using a deep convolutional recurrent neural network with a long short-term memory architecture, which is trained as a regression block, on the fly, over "probability density difference" maps. Our approach is evaluated over widely used pedestrian tracking benchmarks, remarkably outperforming state-of-the-art multi-target filtering algorithms, while giving competitive results when compared with other tracking approaches: The proposed approach generates an average 40.40 and 62.29 optimal sub-pattern assignment (OSPA) errors on MOT15 and MOT16/17 datasets, respectively, while producing 62.0%, 70.0% and 66.9% multi-object tracking accuracy (MOTA) on MOT16/17, PNNL Parking Lot and PETS09 pedestrian tracking datasets, respectively, when publicly available detectors are used.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.00313](http://arxiv.org/abs/1811.00313)

##### PDF
[http://arxiv.org/pdf/1811.00313](http://arxiv.org/pdf/1811.00313)

