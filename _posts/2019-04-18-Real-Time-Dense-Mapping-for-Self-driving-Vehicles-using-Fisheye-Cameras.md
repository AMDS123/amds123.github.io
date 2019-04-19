---
layout: post
title: "Real-Time Dense Mapping for Self-driving Vehicles using Fisheye Cameras"
date: 2019-04-18 16:00:43
categories: arXiv_RO
tags: arXiv_RO Object_Detection Detection
author: Zhaopeng Cui, Lionel Heng, Ye Chuan Yeo, Andreas Geiger, Marc Pollefeys, Torsten Sattler
mathjax: true
---

* content
{:toc}

##### Abstract
We present a real-time dense geometric mapping algorithm for large-scale environments. Unlike existing methods which use pinhole cameras, our implementation is based on fisheye cameras which have larger field of view and benefit some other tasks including Visual-Inertial Odometry, localization and object detection around vehicles. Our algorithm runs on in-vehicle PCs at 15 Hz approximately, enabling vision-only 3D scene perception for self-driving vehicles. For each synchronized set of images captured by multiple cameras, we first compute a depth map for a reference camera using plane-sweeping stereo. To maintain both accuracy and efficiency, while accounting for the fact that fisheye images have a rather low resolution, we recover the depths using multiple image resolutions. We adopt the fast object detection framework YOLOv3 to remove potentially dynamic objects. At the end of the pipeline, we fuse the fisheye depth images into the truncated signed distance function (TSDF) volume to obtain a 3D map. We evaluate our method on large-scale urban datasets, and results show that our method works well even in complex environments.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1809.06132](http://arxiv.org/abs/1809.06132)

##### PDF
[http://arxiv.org/pdf/1809.06132](http://arxiv.org/pdf/1809.06132)

