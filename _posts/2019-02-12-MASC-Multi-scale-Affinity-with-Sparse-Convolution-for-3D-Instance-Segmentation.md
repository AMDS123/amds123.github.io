---
layout: post
title: "MASC: Multi-scale Affinity with Sparse Convolution for 3D Instance Segmentation"
date: 2019-02-12 16:30:54
categories: arXiv_CV
tags: arXiv_CV Sparse Segmentation Prediction
author: Chen Liu, Yasutaka Furukawa
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new approach for 3D instance segmentation based on sparse convolution and point affinity prediction, which indicates the likelihood of two points belonging to the same instance. The proposed network, built upon submanifold sparse convolution [3], processes a voxelized point cloud and predicts semantic scores for each occupied voxel as well as the affinity between neighboring voxels at different scales. A simple yet effective clustering algorithm segments points into instances based on the predicted affinity and the mesh topology. The semantic for each instance is determined by the semantic prediction. Experiments show that our method outperforms the state-of-the-art instance segmentation methods by a large margin on the widely used ScanNet benchmark [2]. We share our code publicly at https://github.com/art-programmer/MASC.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.04478](http://arxiv.org/abs/1902.04478)

##### PDF
[http://arxiv.org/pdf/1902.04478](http://arxiv.org/pdf/1902.04478)

