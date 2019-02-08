---
layout: post
title: "Real-time 3D Traffic Cone Detection for Autonomous Driving"
date: 2019-02-06 20:45:30
categories: arXiv_CV
tags: arXiv_CV Regularization Object_Detection Detection
author: Ankit Dhall, Dengxin Dai, Luc Van Gool
mathjax: true
---

* content
{:toc}

##### Abstract
Considerable progress has been made in semantic scene understanding of road scenes with monocular cameras. It is, however, mainly related to certain classes such as cars and pedestrians. This work investigates traffic cones, an object class crucial for traffic control in the context of autonomous vehicles. 3D object detection using images from a monocular camera is intrinsically an ill-posed problem. In this work, we leverage the unique structure of traffic cones and propose a pipelined approach to the problem. Specifically, we first detect cones in images by a tailored 2D object detector; then, the spatial arrangement of keypoints on a traffic cone are detected by our deep structural regression network, where the fact that the cross-ratio is projection invariant is leveraged for network regularization; finally, the 3D position of cones is recovered by the classical Perspective n-Point algorithm. Extensive experiments show that our approach can accurately detect traffic cones and estimate their position in the 3D world in real time. The proposed method is also deployed on a real-time, critical system. It runs efficiently on the low-power Jetson TX2, providing accurate 3D position estimates, allowing a race-car to map and drive autonomously on an unseen track indicated by traffic cones. With the help of robust and accurate perception, our race-car won both Formula Student Competitions held in Italy and Germany in 2018, cruising at a top-speed of 54 kmph. Visualization of the complete pipeline, mapping and navigation can be found on our project page.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.02394](http://arxiv.org/abs/1902.02394)

##### PDF
[http://arxiv.org/pdf/1902.02394](http://arxiv.org/pdf/1902.02394)

