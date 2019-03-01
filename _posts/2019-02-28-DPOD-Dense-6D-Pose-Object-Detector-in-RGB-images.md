---
layout: post
title: "DPOD: Dense 6D Pose Object Detector in RGB images"
date: 2019-02-28 11:15:02
categories: arXiv_CV
tags: arXiv_CV Object_Detection Pose_Estimation Detection
author: Sergey Zakharov, Ivan Shugurov, Slobodan Ilic
mathjax: true
---

* content
{:toc}

##### Abstract
In this work we propose a new method for simultaneous object detection and 6DoF pose estimation. Unlike most recent techniques for CNN-based object detection and pose estimation, we do not base our approach on the common 2D counterparts, i.e. SSD and YOLO, but propose a new scheme. Instead of regressing 2D or 3D bounding boxes, we output full-sized 2D images containing multiclass object masks and dense 2D-3D correspondences. Having them at hand, a 6D pose is computed for each detected object using the PnP algorithm supplemented with RANSAC. This strategy allows for substantially better pose estimates due to a much higher number of relevant pose correspondences. Furthermore, the method is real-time capable, conceptually simple and not bound to any particular detection paradigms, such as R-CNN, SSD or YOLO. We test our method for single- and multiple-object pose estimation and compare the performance with the former state-of-the-art approaches. Moreover, we demonstrate how to use our pipeline when only synthetic renderings are available. In both cases, we outperform the former state-of-the-art by a large margin.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.11020](http://arxiv.org/abs/1902.11020)

##### PDF
[http://arxiv.org/pdf/1902.11020](http://arxiv.org/pdf/1902.11020)

