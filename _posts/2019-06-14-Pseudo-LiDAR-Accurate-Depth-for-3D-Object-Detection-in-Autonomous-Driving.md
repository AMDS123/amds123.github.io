---
layout: post
title: "Pseudo-LiDAR++: Accurate Depth for 3D Object Detection in Autonomous Driving"
date: 2019-06-14 17:36:11
categories: arXiv_CV
tags: arXiv_CV Object_Detection Sparse Detection
author: Yurong You, Yan Wang, Wei-Lun Chao, Divyansh Garg, Geoff Pleiss, Bharath Hariharan, Mark Campbell, Kilian Q. Weinberger
mathjax: true
---

* content
{:toc}

##### Abstract
Detecting objects such as cars and pedestrians in 3D plays an indispensable role in autonomous driving. Existing approaches largely rely on expensive LiDAR sensors for accurate depth information. While recently pseudo-LiDAR has been introduced as a promising alternative, at a much lower cost based solely on stereo images, there is still a notable performance gap. In this paper we provide substantial advances to the pseudo-LiDAR framework through improvements in stereo depth estimation. Concretely, we adapt the stereo network architecture and loss function to be more aligned with accurate depth estimation of far away objects (currently the primary weakness of pseudo-LiDAR). Further, we explore the idea to leverage cheaper but extremely sparse LiDAR sensors, which alone provide insufficient information for 3D detection, to de-bias our depth estimation. We propose a depth-propagation algorithm, guided by the initial depth estimates, to diffuse these few exact measurements across the entire depth map. We show on the KITTI object detection benchmark that our combined approach yields substantial improvements in depth estimation and stereo-based 3D object detection --- outperforming the previous state-of-the-art detection accuracy for far-away objects by 40%. Our code will be publicly available at this https URL.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1906.06310](https://arxiv.org/abs/1906.06310)

##### PDF
[https://arxiv.org/pdf/1906.06310](https://arxiv.org/pdf/1906.06310)

