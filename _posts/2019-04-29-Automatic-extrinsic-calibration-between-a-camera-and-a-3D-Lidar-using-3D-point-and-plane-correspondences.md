---
layout: post
title: "Automatic extrinsic calibration between a camera and a 3D Lidar using 3D point and plane correspondences"
date: 2019-04-29 03:08:33
categories: arXiv_CV
tags: arXiv_CV
author: Surabhi Verma, Julie Stephany Berrio, Stewart Worrall, Eduardo Nebot
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes an automated method to obtain the extrinsic calibration parameters between a camera and a 3D lidar with as low as 16 beams. We use a checkerboard as a reference to obtain features of interest in both sensor frames. The calibration board centre point and normal vector are automatically extracted from the lidar point cloud by exploiting the geometry of the board. The corresponding features in the camera image are obtained from the camera's extrinsic matrix. We explain the reasons behind selecting these features, and why they are more robust compared to other possibilities. To obtain the optimal extrinsic parameters, we choose a genetic algorithm to address the highly non-linear state space. The process is automated after defining the bounds of the 3D experimental region relative to the lidar, and the true board dimensions. In addition, the camera is assumed to be intrinsically calibrated. Our method requires a minimum of 3 checkerboard poses, and the calibration accuracy is demonstrated by evaluating our algorithm using real world and simulated features.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.12433](http://arxiv.org/abs/1904.12433)

##### PDF
[http://arxiv.org/pdf/1904.12433](http://arxiv.org/pdf/1904.12433)

