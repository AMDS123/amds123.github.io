---
layout: post
title: "GS3D: An Efficient 3D Object Detection Framework for Autonomous Driving"
date: 2019-03-26 15:25:26
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face Classification Detection
author: Buyu Li, Wanli Ouyang, Lu Sheng, Xingyu Zeng, Xiaogang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
We present an efficient 3D object detection framework based on a single RGB image in the scenario of autonomous driving. Our efforts are put on extracting the underlying 3D information in a 2D image and determining the accurate 3D bounding box of the object without point cloud or stereo data. Leveraging the off-the-shelf 2D object detector, we propose an artful approach to efficiently obtain a coarse cuboid for each predicted 2D box. The coarse cuboid has enough accuracy to guide us to determine the 3D box of the object by refinement. In contrast to previous state-of-the-art methods that only use the features extracted from the 2D bounding box for box refinement, we explore the 3D structure information of the object by employing the visual features of visible surfaces. The new features from surfaces are utilized to eliminate the problem of representation ambiguity brought by only using a 2D bounding box. Moreover, we investigate different methods of 3D box refinement and discover that a classification formulation with quality aware loss has much better performance than regression. Evaluated on the KITTI benchmark, our approach outperforms current state-of-the-art methods for single RGB image based 3D object detection.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.10955](http://arxiv.org/abs/1903.10955)

##### PDF
[http://arxiv.org/pdf/1903.10955](http://arxiv.org/pdf/1903.10955)

