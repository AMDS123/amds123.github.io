---
layout: post
title: "Depth map estimation methodology for detecting free-obstacle navigation areas"
date: 2019-05-15 04:57:53
categories: arXiv_CV
tags: arXiv_CV
author: Sergio Trejo, Karla Martinez, Gerardo Flores
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a vision-based methodology which makes use of a stereo camera rig and a one dimension LiDAR to estimate free obstacle areas for quadrotor navigation. The presented approach fuses information provided by a depth map from a stereo camera rig, and the sensing distance of the 1D-LiDAR. Once the depth map is filtered with a Weighted Least Squares filter (WLS), the information is fused through a Kalman filter algorithm. To determine if there is a free space large enough for the quadrotor to pass through, our approach marks an area inside the disparity map by using the Kalman Filter output information. The whole process is implemented in an embedded computer Jetson TX2 and coded in the Robotic Operating System (ROS). Experiments demonstrate the effectiveness of our approach.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.05946](http://arxiv.org/abs/1905.05946)

##### PDF
[http://arxiv.org/pdf/1905.05946](http://arxiv.org/pdf/1905.05946)

