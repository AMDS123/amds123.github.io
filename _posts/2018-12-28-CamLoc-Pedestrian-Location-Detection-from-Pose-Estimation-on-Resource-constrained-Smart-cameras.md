---
layout: post
title: "CamLoc: Pedestrian Location Detection from Pose Estimation on Resource-constrained Smart-cameras"
date: 2018-12-28 19:57:48
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Inference Detection Recognition
author: Adrian Cosma, Ion Emilian Radoi, Valentin Radu
mathjax: true
---

* content
{:toc}

##### Abstract
Recent advancements in energy-efficient hardware technology is driving the exponential growth we are experiencing in the Internet of Things (IoT) space, with more pervasive computations being performed near to data generation sources. A range of intelligent devices and applications performing local detection is emerging (activity recognition, fitness monitoring, etc.) bringing with them obvious advantages such as reducing detection latency for improved interaction with devices and safeguarding user data by not leaving the device. Video processing holds utility for many emerging applications and data labelling in the IoT space. However, performing this video processing with deep neural networks at the edge of the Internet is not trivial. In this paper we show that pedestrian location estimation using deep neural networks is achievable on fixed cameras with limited compute resources. Our approach uses pose estimation from key body points detection to extend pedestrian skeleton when whole body not in image (occluded by obstacles or partially outside of frame), which achieves better location estimation performance (infrence time and memory footprint) compared to fitting a bounding box over pedestrian and scaling. We collect a sizable dataset comprising of over 2100 frames in videos from one and two surveillance cameras pointing from different angles at the scene, and annotate each frame with the exact position of person in image, in 42 different scenarios of activity and occlusion. We compare our pose estimation based location detection with a popular detection algorithm, YOLOv2, for overlapping bounding-box generation, our solution achieving faster inference time (15x speedup) at half the memory footprint, within resource capabilities on embedded devices, which demonstrate that CamLoc is an efficient solution for location estimation in videos on smart-cameras.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.11209](http://arxiv.org/abs/1812.11209)

##### PDF
[http://arxiv.org/pdf/1812.11209](http://arxiv.org/pdf/1812.11209)

