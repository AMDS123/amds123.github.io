---
layout: post
title: "GN-Net: The Gauss-Newton Loss for Deep Direct SLAM"
date: 2019-04-26 16:58:34
categories: arXiv_CV
tags: arXiv_CV Tracking SLAM
author: Lukas von Stumberg, Patrick Wenzel, Qadeer Khan, Daniel Cremers
mathjax: true
---

* content
{:toc}

##### Abstract
Direct methods for SLAM have shown exceptional performance on odometry tasks. However, they still suffer from dynamic lighting/weather changes and from a bad initialization on large baselines. To mitigate both of these effects, we propose an approach which feeds deep visual descriptors for each pixel as input to the SLAM system. In this work, we introduce GN-Net: a network optimized with the novel Gauss-Newton loss for training deep features. It is designed to maximize the probability of the correct pixel correspondence inside the Gauss-Newton algorithm. This results in features with a larger convergence basin when compared with single-channel grayscale images generally used in SLAM-based approaches. Our network can be trained with ground-truth pixel correspondences between different images, produced either from simulation data or by any state-of-the-art SLAM algorithm. We show that our approach is more robust against bad initialization, variations in day-time, and weather changes thereby outperforming state-of-the-art direct and indirect methods. Furthermore, we release an evaluation benchmark for what we refer to as relocalization tracking. It has been created using the CARLA simulator as well as sequences taken from the Oxford RobotCar Dataset.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.11932](http://arxiv.org/abs/1904.11932)

##### PDF
[http://arxiv.org/pdf/1904.11932](http://arxiv.org/pdf/1904.11932)

