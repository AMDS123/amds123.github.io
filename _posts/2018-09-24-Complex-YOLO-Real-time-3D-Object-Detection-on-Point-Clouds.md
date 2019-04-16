---
layout: post
title: "Complex-YOLO: Real-time 3D Object Detection on Point Clouds"
date: 2018-09-24 09:27:33
categories: arXiv_CV
tags: arXiv_CV Object_Detection Sparse Prediction Detection
author: Martin Simon, Stefan Milz, Karl Amende, Horst-Michael Gross
mathjax: true
---

* content
{:toc}

##### Abstract
Lidar based 3D object detection is inevitable for autonomous driving, because it directly links to environmental understanding and therefore builds the base for prediction and motion planning. The capacity of inferencing highly sparse 3D data in real-time is an ill-posed problem for lots of other application areas besides automated vehicles, e.g. augmented reality, personal robotics or industrial automation. We introduce Complex-YOLO, a state of the art real-time 3D object detection network on point clouds only. In this work, we describe a network that expands YOLOv2, a fast 2D standard object detector for RGB images, by a specific complex regression strategy to estimate multi-class 3D boxes in Cartesian space. Thus, we propose a specific Euler-Region-Proposal Network (E-RPN) to estimate the pose of the object by adding an imaginary and a real fraction to the regression network. This ends up in a closed complex space and avoids singularities, which occur by single angle estimations. The E-RPN supports to generalize well during training. Our experiments on the KITTI benchmark suite show that we outperform current leading methods for 3D object detection specifically in terms of efficiency. We achieve state of the art results for cars, pedestrians and cyclists by being more than five times faster than the fastest competitor. Further, our model is capable of estimating all eight KITTI-classes, including Vans, Trucks or sitting pedestrians simultaneously with high accuracy.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1803.06199](https://arxiv.org/abs/1803.06199)

##### PDF
[https://arxiv.org/pdf/1803.06199](https://arxiv.org/pdf/1803.06199)

