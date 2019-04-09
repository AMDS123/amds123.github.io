---
layout: post
title: "Probabilistic Regression of Rotations using Quaternion Averaging and a Deep Multi-Headed Network"
date: 2019-04-01 19:39:09
categories: arXiv_CV
tags: arXiv_CV
author: Valentin Peretroukhin, Brandon Wagstaff, Matthew Giamou, Jonathan Kelly
mathjax: true
---

* content
{:toc}

##### Abstract
Accurate estimates of rotation are crucial to vision-based motion estimation in augmented reality and robotics. In this work, we present a method to extract probabilistic estimates of rotation from deep regression models. First, we build on prior work and argue that a multi-headed network structure we name HydraNet provides better calibrated uncertainty estimates than methods that rely on stochastic forward passes. Second, we extend HydraNet to targets that belong to the rotation group, SO(3), by regressing unit quaternions and using the tools of rotation averaging and uncertainty injection onto the manifold to produce three-dimensional covariances. Finally, we present results and analysis on a synthetic dataset, learn consistent orientation estimates on the 7-Scenes dataset, and show how we can use our learned covariances to fuse deep estimates of relative orientation with classical stereo visual odometry to improve localization on the KITTI dataset.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.03182](http://arxiv.org/abs/1904.03182)

##### PDF
[http://arxiv.org/pdf/1904.03182](http://arxiv.org/pdf/1904.03182)

