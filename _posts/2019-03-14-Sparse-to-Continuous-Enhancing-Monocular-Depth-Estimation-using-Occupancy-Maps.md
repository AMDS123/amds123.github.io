---
layout: post
title: "Sparse-to-Continuous: Enhancing Monocular Depth Estimation using Occupancy Maps"
date: 2019-03-14 19:56:22
categories: arXiv_CV
tags: arXiv_CV Sparse Face Optimization Prediction
author: N&#xed;colas Rosa, Vitor Guizilini, Valdir Grassi Jr
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the problem of single image depth estimation (SIDE), focusing on improving the accuracy of deep neural network predictions. In a supervised learning scenario, the quality of predictions is intrinsically related to the training labels, which guide the optimization process. For indoor scenes, structured-light-based depth sensors (e.g. Kinect) are able to provide dense, albeit short-range, depth maps. On the other hand, for outdoor scenes, LiDARs are still considered the standard sensor, which comparatively provide much sparser measurements, especially in areas further away. Rather than modifying the neural network structure to deal with sparse depth maps, this paper introduces a novel technique for the densification of depth maps based on the Hilbert Maps framework. A continuous occupancy map is produced based on 3D points from LiDAR scans, and the resulting reconstructed surface is projected into a 2D depth map with arbitrary resolution. Experiments conducted with various subsets of the KITTI dataset show the improvement produced by the proposed Sparse-to-Continuous technique, without the introduction of extra information into the training methodology.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1809.09061](http://arxiv.org/abs/1809.09061)

##### PDF
[http://arxiv.org/pdf/1809.09061](http://arxiv.org/pdf/1809.09061)

