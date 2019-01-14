---
layout: post
title: "A General Optimization-based Framework for Global Pose Estimation with Multiple Sensors"
date: 2019-01-11 16:41:12
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Optimization
author: Tong Qin, Shaozu Cao, Jie Pan, Shaojie Shen
mathjax: true
---

* content
{:toc}

##### Abstract
Accurate state estimation is a fundamental problem for autonomous robots. To achieve locally accurate and globally drift-free state estimation, multiple sensors with complementary properties are usually fused together. Local sensors (camera, IMU, LiDAR, etc) provide precise pose within a small region, while global sensors (GPS, magnetometer, barometer, etc) supply noisy but globally drift-free localization in a large-scale environment. In this paper, we propose a sensor fusion framework to fuse local states with global sensors, which achieves locally accurate and globally drift-free pose estimation. Local estimations, produced by existing VO/VIO approaches, are fused with global sensors in a pose graph optimization. Within the graph optimization, local estimations are aligned into a global coordinate. Meanwhile, the accumulated drifts are eliminated. We evaluate the performance of our system on public datasets and with real-world experiments. Results are compared against other state-of-the-art algorithms. We highlight that our system is a general framework, which can easily fuse various global sensors in a unified pose graph optimization. Our implementations are open source\footnote{https://github.com/HKUST-Aerial-Robotics/VINS-Fusion}.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.03642](http://arxiv.org/abs/1901.03642)

##### PDF
[http://arxiv.org/pdf/1901.03642](http://arxiv.org/pdf/1901.03642)

