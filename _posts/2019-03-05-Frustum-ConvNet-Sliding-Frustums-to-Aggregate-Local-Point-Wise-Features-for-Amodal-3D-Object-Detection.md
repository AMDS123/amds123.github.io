---
layout: post
title: "Frustum ConvNet: Sliding Frustums to Aggregate Local Point-Wise Features for Amodal 3D Object Detection"
date: 2019-03-05 14:46:58
categories: arXiv_CV
tags: arXiv_CV Object_Detection Knowledge CNN Detection
author: Zhixin Wang, Kui Jia
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we propose a novel method termed Frustum ConvNet (F-ConvNet) for amodal 3D object detection from point clouds. Given 2D region proposals in a RGB image, our method first generates a sequence of frustums for each region proposal, and uses the obtained frustums to group local points. F-ConvNet aggregates point-wise features as frustumlevel feature vectors, and arrays these feature vectors as a feature map for use of its subsequent component of fully convolutional network (FCN), which spatially fuses frustumlevel features and supports an end-to-end and continuous estimation of oriented boxes in the 3D space. We also propose component variants of L-ConvNet, including a FCN variant that extracts multi-resolution frustum features, and a refined use of L-ConvNet over a reduced 3D space. Careful ablation studies verify the efficacy of these component variants. LConvNet assumes no prior knowledge of the working 3D environment, and is thus dataset-agnostic. We present experiments on both the indoor SUN-RGBD and outdoor KITTI datasets. LConvNet outperforms all existing methods on SUN-RGBD, and at the time of submission it outperforms all published works on the KITTI benchmark. We will make the code of L-ConvNet publicly available.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1903.01864](https://arxiv.org/abs/1903.01864)

##### PDF
[https://arxiv.org/pdf/1903.01864](https://arxiv.org/pdf/1903.01864)

