---
layout: post
title: "3D Object Proposals using Stereo Imagery for Accurate Object Class Detection"
date: 2017-04-25 07:58:07
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Xiaozhi Chen, Kaustav Kundu, Yukun Zhu, Huimin Ma, Sanja Fidler, Raquel Urtasun
mathjax: true
---

* content
{:toc}

##### Abstract
The goal of this paper is to perform 3D object detection in the context of autonomous driving. Our method first aims at generating a set of high-quality 3D object proposals by exploiting stereo imagery. We formulate the problem as minimizing an energy function that encodes object size priors, placement of objects on the ground plane as well as several depth informed features that reason about free space, point cloud densities and distance to the ground. We then exploit a CNN on top of these proposals to perform object detection. In particular, we employ a convolutional neural net (CNN) that exploits context and depth information to jointly regress to 3D bounding box coordinates and object pose. Our experiments show significant performance gains over existing RGB and RGB-D object proposal methods on the challenging KITTI benchmark. When combined with the CNN, our approach outperforms all existing results in object detection and orientation estimation tasks for all three KITTI object classes. Furthermore, we experiment also with the setting where LIDAR information is available, and show that using both LIDAR and stereo leads to the best result.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1608.07711](https://arxiv.org/abs/1608.07711)

##### PDF
[https://arxiv.org/pdf/1608.07711](https://arxiv.org/pdf/1608.07711)

