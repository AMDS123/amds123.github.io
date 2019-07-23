---
layout: post
title: "A Single Image based Head Pose Estimation Method with Spherical Parameterization"
date: 2019-07-22 10:16:30
categories: arXiv_CV
tags: arXiv_CV Face Pose_Estimation
author: Hui Yuana, Mengyu Lia, Junhui Hou, Jimin Xiao
mathjax: true
---

* content
{:toc}

##### Abstract
Head pose estimation plays a vital role in various applications, e.g., driverassistance systems, human-computer interaction, virtual reality technology, and so on. We propose a novel geometry based algorithm for accurately estimating the head pose from a single 2D face image at a very low computational cost. Specifically, the rectangular coordinates of only four non-coplanar feature points from a predefined 3D facial model as well as the corresponding ones automatically/ manually extracted from a 2D face image are first normalized to exclude the effect of external factors (i.e., scale factor and translation parameters). Then, the four normalized 3D feature points are represented in spherical coordinates with reference to the uniquely determined sphere by themselves. Due to the spherical parameterization, the coordinates of feature points can then be morphed along all the three directions in the rectangular coordinates effectively. Finally, the rotation matrix indicating the head pose is obtained by minimizing the Euclidean distance between the normalized 2D feature points and the 2D re-projections of morphed 3D feature points. Comprehensive experimental results over two popular databases, i.e., Pointing'04 and Biwi Kinect, demonstrate that the proposed algorithm can estimate head poses with higher accuracy and lower run time than state-of-the-art geometry based methods. Even compared with start-of-the-art learning based methods or geometry based methods with additional depth information, our algorithm still produces comparable performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.09217](http://arxiv.org/abs/1907.09217)

##### PDF
[http://arxiv.org/pdf/1907.09217](http://arxiv.org/pdf/1907.09217)

