---
layout: post
title: "Real-time Dynamic Object Detection for Autonomous Driving using Prior 3D-Maps"
date: 2018-09-28 14:04:31
categories: arXiv_CV
tags: arXiv_CV Object_Detection Tracking Classification Detection
author: B Ravi Kiran, Luis Roldao, Benat Irastorza, Renzo Verastegui, Sebastian Suss, Senthil Yogamani, Victor Talpaert, Alexandre Lepoutre, Guillaume Trehard
mathjax: true
---

* content
{:toc}

##### Abstract
Lidar has become an essential sensor for autonomous driving as it provides reliable depth estimation. Lidar is also the primary sensor used in building 3D maps which can be used even in the case of low-cost systems which do not use Lidar. Computation on Lidar point clouds is intensive as it requires processing of millions of points per second. Additionally there are many subsequent tasks such as clustering, detection, tracking and classification which makes real-time execution challenging. In this paper, we discuss real-time dynamic object detection algorithms which leverages previously mapped Lidar point clouds to reduce processing. The prior 3D maps provide a static background model and we formulate dynamic object detection as a background subtraction problem. Computation and modeling challenges in the mapping and online execution pipeline are described. We propose a rejection cascade architecture to subtract road regions and other 3D regions separately. We implemented an initial version of our proposed algorithm and evaluated the accuracy on CARLA simulator.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1809.11036](https://arxiv.org/abs/1809.11036)

##### PDF
[https://arxiv.org/pdf/1809.11036](https://arxiv.org/pdf/1809.11036)

