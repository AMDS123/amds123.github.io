---
layout: post
title: "Deep Hough Voting for 3D Object Detection in Point Clouds"
date: 2019-04-21 21:36:36
categories: arXiv_CV
tags: arXiv_CV Object_Detection Sparse Face Detection
author: Charles R. Qi, Or Litany, Kaiming He, Leonidas J. Guibas
mathjax: true
---

* content
{:toc}

##### Abstract
Current 3D object detection methods are heavily influenced by 2D detectors. In order to leverage architectures in 2D detectors, they often convert 3D point clouds to regular grids (i.e., to voxel grids or to bird's eye view images), or rely on detection in 2D images to propose 3D boxes. Few works have attempted to directly detect objects in point clouds. In this work, we return to first principles to construct a 3D detection pipeline for point cloud data and as generic as possible. However, due to the sparse nature of the data -- samples from 2D manifolds in 3D space -- we face a major challenge when directly predicting bounding box parameters from scene points: a 3D object centroid can be far from any surface point thus hard to regress accurately in one step. To address the challenge, we propose VoteNet, an end-to-end 3D object detection network based on a synergy of deep point set networks and Hough voting. Our model achieves state-of-the-art 3D detection on two large datasets of real 3D scans, ScanNet and SUN RGB-D with a simple design, compact model size and high efficiency. Remarkably, VoteNet outperforms previous methods by using purely geometric information without relying on color images.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.09664](http://arxiv.org/abs/1904.09664)

##### PDF
[http://arxiv.org/pdf/1904.09664](http://arxiv.org/pdf/1904.09664)

