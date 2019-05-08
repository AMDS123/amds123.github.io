---
layout: post
title: "Collaborative Localization for Micro Aerial Vehicles"
date: 2019-05-07 15:45:44
categories: arXiv_RO
tags: arXiv_RO Salient Sparse Pose_Estimation Tracking Detection
author: Sai Vemprala, Srikanth Saripalli
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a framework for performing collaborative localization for groups of micro aerial vehicles (MAV) that use vision based sensing. The vehicles are each assumed to be equipped with a forward-facing monocular camera, and to be capable of communicating with each other. This collaborative localization approach is developed as a decentralized algorithm and built in a distributed fashion where individual and relative pose estimation techniques are combined for the group to localize against surrounding environments. The MAVs initially detect and match salient features between each other to create a sparse reconstruction of the observed environment, which acts as a global map. Once a map is available, each MAV performs feature detection and tracking with a robust outlier rejection process to estimate its own pose in 6 degrees of freedom. Occasionally, one or more MAVs can be tasked to compute poses for another MAV through relative measurements, which is achieved through multiple view geometry concepts. These relative measurements are then fused with individual measurements in a consistent fashion. We present the results of the algorithm on image data from MAV flights both in simulation and real life, and discuss the advantages of collaborative localization in improving pose estimation accuracy.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.02648](http://arxiv.org/abs/1905.02648)

##### PDF
[http://arxiv.org/pdf/1905.02648](http://arxiv.org/pdf/1905.02648)

