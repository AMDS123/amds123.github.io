---
layout: post
title: "Efficient Pose Selection for Interactive Camera Calibration"
date: 2019-07-09 11:44:40
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Pavel Rojtberg, Arjan Kuijper
mathjax: true
---

* content
{:toc}

##### Abstract
The choice of poses for camera calibration with planar patterns is only rarely considered - yet the calibration precision heavily depends on it. This work presents a pose selection method that finds a compact and robust set of calibration poses and is suitable for interactive calibration. Consequently, singular poses that would lead to an unreliable solution are avoided explicitly, while poses reducing the uncertainty of the calibration are favoured. For this, we use uncertainty propagation. 
 Our method takes advantage of a self-identifying calibration pattern to track the camera pose in real-time. This allows to iteratively guide the user to the target poses, until the desired quality level is reached. Therefore, only a sparse set of key-frames is needed for calibration. 
 The method is evaluated on separate training and testing sets, as well as on synthetic data. Our approach performs better than comparable solutions while requiring 30% less calibration frames.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.04096](http://arxiv.org/abs/1907.04096)

##### PDF
[http://arxiv.org/pdf/1907.04096](http://arxiv.org/pdf/1907.04096)

