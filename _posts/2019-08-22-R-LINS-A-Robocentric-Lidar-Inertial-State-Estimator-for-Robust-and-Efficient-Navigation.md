---
layout: post
title: "R-LINS: A Robocentric Lidar-Inertial State Estimator for Robust and Efficient Navigation"
date: 2019-08-22 07:47:28
categories: arXiv_RO
tags: arXiv_RO
author: Chao Qin, Haoyang Ye, Christian E. Pranata, Jun Han, Shuyang Zhang, Ming Liu
mathjax: true
---

* content
{:toc}

##### Abstract
We present R-LINS, a lightweight robocentric lidar-inertial state estimator, which estimates robot ego-motion using a 6-axis IMU and a 3D lidar in a tightly-coupled scheme. To achieve robustness and computational efficiency even in challenging environments, an iterated error-state Kalman filter (ESKF) is designed, which recursively corrects the state via repeatedly generating new corresponding feature pairs. Moreover, a novel robocentric formulation is adopted in which we reformulate the state estimator concerning a moving local frame, rather than a fixed global frame as in the standard world-centric lidar-inertial odometry(LIO), in order to prevent filter divergence and lower computational cost. To validate generalizability and long-time practicability, extensive experiments are performed in indoor and outdoor scenarios. The results indicate that R-LINS outperforms lidar-only and loosely-coupled algorithms, and achieve competitive performance as the state-of-the-art LIO with close to an order-of-magnitude improvement in terms of speed.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.02233](http://arxiv.org/abs/1907.02233)

##### PDF
[http://arxiv.org/pdf/1907.02233](http://arxiv.org/pdf/1907.02233)

