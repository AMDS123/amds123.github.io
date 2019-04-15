---
layout: post
title: "AI-IMU Dead-Reckoning"
date: 2019-04-12 07:02:53
categories: arXiv_RO
tags: arXiv_RO
author: Martin Brossard (CAOR), Axel Barrau, Silv&#xe8;re Bonnabel (CAOR)
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we propose a novel accurate method for dead-reckoning of wheeled vehicles based only on an Inertial Measurement Unit (IMU). In the context of intelligent vehicles, robust and accurate dead-reckoning based on the IMU may prove useful to correlate feeds from imaging sensors, to safely navigate through obstructions, or for safe emergency stops in the extreme case of exteroceptive sensors failure. The key components of the method are the Kalman filter and the use of deep neural networks to dynamically adapt the noise parameters of the filter. The method is tested on the KITTI odometry dataset, and our dead-reckoning inertial method based only on the IMU accurately estimates 3D position, velocity, orientation of the vehicle and self-calibrates the IMU biases. We achieve on average a 1.10% translational error and the algorithm competes with top-ranked methods which, by contrast, use LiDAR or stereo vision. We make our implementation open-source at: https://github.com/mbrossar/ai-imu-dr

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.06064](http://arxiv.org/abs/1904.06064)

##### PDF
[http://arxiv.org/pdf/1904.06064](http://arxiv.org/pdf/1904.06064)

