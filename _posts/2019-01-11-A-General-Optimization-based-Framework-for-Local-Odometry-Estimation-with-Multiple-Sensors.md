---
layout: post
title: "A General Optimization-based Framework for Local Odometry Estimation with Multiple Sensors"
date: 2019-01-11 16:31:28
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Tong Qin, Jie Pan, Shaozu Cao, Shaojie Shen
mathjax: true
---

* content
{:toc}

##### Abstract
Nowadays, more and more sensors are equipped on robots to increase robustness and autonomous ability. We have seen various sensor suites equipped on different platforms, such as stereo cameras on ground vehicles, a monocular camera with an IMU (Inertial Measurement Unit) on mobile phones, and stereo cameras with an IMU on aerial robots. Although many algorithms for state estimation have been proposed in the past, they are usually applied to a single sensor or a specific sensor suite. Few of them can be employed with multiple sensor choices. In this paper, we proposed a general optimization-based framework for odometry estimation, which supports multiple sensor sets. Every sensor is treated as a general factor in our framework. Factors which share common state variables are summed together to build the optimization problem. We further demonstrate the generality with visual and inertial sensors, which form three sensor suites (stereo cameras, a monocular camera with an IMU, and stereo cameras with an IMU). We validate the performance of our system on public datasets and through real-world experiments with multiple sensors. Results are compared against other state-of-the-art algorithms. We highlight that our system is a general framework, which can easily fuse various sensors in a pose graph optimization. Our implementations are open source\footnote{https://github.com/HKUST-Aerial-Robotics/VINS-Fusion}.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.03638](http://arxiv.org/abs/1901.03638)

##### PDF
[http://arxiv.org/pdf/1901.03638](http://arxiv.org/pdf/1901.03638)

