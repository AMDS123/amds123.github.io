---
layout: post
title: "LU-Net: An Efficient Network for 3D LiDAR Point Cloud Semantic Segmentation Based on End-to-End-Learned 3D Features and U-Net"
date: 2019-08-30 11:28:59
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation
author: Pierre Biasutti, Vincent Lepetit, Jean-Fran&#xe7;ois Aujol, Mathieu Br&#xe9;dif, Aur&#xe9;lie Bugeau
mathjax: true
---

* content
{:toc}

##### Abstract
We propose LU-Net -- for LiDAR U-Net, a new method for the semantic segmentation of a 3D LiDAR point cloud. Instead of applying some global 3D segmentation method such as PointNet, we propose an end-to-end architecture for LiDAR point cloud semantic segmentation that efficiently solves the problem as an image processing problem. We first extract high-level 3D features for each point given its 3D neighbors. Then, these features are projected into a 2D multichannel range-image by considering the topology of the sensor. Thanks to these learned features and this projection, we can finally perform the segmentation using a simple U-Net segmentation network, which performs very well while being very efficient. In this way, we can exploit both the 3D nature of the data and the specificity of the LiDAR sensor. This approach outperforms the state-of-the-art by a large margin on the KITTI dataset, as our experiments show. Moreover, this approach operates at 24fps on a single GPU. This is above the acquisition rate of common LiDAR sensors which makes it suitable for real-time applications.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.11656](http://arxiv.org/abs/1908.11656)

##### PDF
[http://arxiv.org/pdf/1908.11656](http://arxiv.org/pdf/1908.11656)

