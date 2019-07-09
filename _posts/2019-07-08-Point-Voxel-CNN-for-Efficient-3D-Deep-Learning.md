---
layout: post
title: "Point-Voxel CNN for Efficient 3D Deep Learning"
date: 2019-07-08 17:48:45
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Deep_Learning Detection
author: Zhijian Liu, Haotian Tang, Yujun Lin, Song Han
mathjax: true
---

* content
{:toc}

##### Abstract
We present Point-Voxel CNN (PVCNN) for efficient, fast 3D deep learning. Previous work processes 3D data using either voxel-based or point-based NN models. However, both approaches are computationally inefficient. The computation cost and memory footprints of the voxel-based models grow cubically with the input resolution, making it memory-prohibitive to scale up the resolution. As for point-based networks, up to 80% of the time is wasted on structuring the irregular data which have rather poor memory locality, not on the actual feature extraction. In this paper, we propose PVCNN that represents the 3D input data in points to reduce the memory consumption, while performing the convolutions in voxels to largely reduce the irregular data access and improve the locality. Our PVCNN model is both memory and computation efficient. Evaluated on semantic and part segmentation datasets, it achieves much higher accuracy than the voxel-based baseline with 10x GPU memory reduction; it also outperforms the state-of-the-art point-based models with 7x measured speedup on average. Remarkably, narrower version of PVCNN achieves 2x speedup over PointNet (an extremely efficient model) on part and scene segmentation benchmarks with much higher accuracy. We validate the general effectiveness of our PVCNN on 3D object detection: by replacing the primitives in Frustrum PointNet with PVConv, it outperforms Frustrum PointNet++ by 2.4% mAP on average with 1.5x measured speedup and GPU memory reduction.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.03739](http://arxiv.org/abs/1907.03739)

##### PDF
[http://arxiv.org/pdf/1907.03739](http://arxiv.org/pdf/1907.03739)

