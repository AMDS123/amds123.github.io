---
layout: post
title: "Part-A^2 Net: 3D Part-Aware and Aggregation Neural Network for Object Detection from Point Cloud"
date: 2019-07-08 15:19:48
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Shaoshuai Shi, Zhe Wang, Xiaogang Wang, Hongsheng Li
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose the part-aware and aggregation neural network (Part-A^2 net) for 3D object detection from point cloud. The whole framework consists of the part-aware stage and the part-aggregation stage. Firstly, the part-aware stage learns to simultaneously predict coarse 3D proposals and accurate intra-object part locations with the free-of-charge supervisions derived from 3D ground-truth boxes. The predicted intra-object part locations within the same proposals are grouped by our new-designed RoI-aware point cloud pooling module, which results in an effective representation to encode the features of 3D proposals. Then the part-aggregation stage learns to re-score the box and refine the box location based on the pooled part locations. We present extensive experiments on the KITTI 3D object detection dataset, which demonstrate that both the predicted intra-object part locations and the proposed RoI-aware point cloud pooling scheme benefit 3D object detection and our Part-A^2 net outperforms state-of-the-art methods by utilizing only point cloud data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.03670](http://arxiv.org/abs/1907.03670)

##### PDF
[http://arxiv.org/pdf/1907.03670](http://arxiv.org/pdf/1907.03670)

