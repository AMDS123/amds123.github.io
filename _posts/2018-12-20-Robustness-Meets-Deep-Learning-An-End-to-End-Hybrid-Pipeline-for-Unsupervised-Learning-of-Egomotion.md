---
layout: post
title: "Robustness Meets Deep Learning: An End-to-End Hybrid Pipeline for Unsupervised Learning of Egomotion"
date: 2018-12-20 03:51:47
categories: arXiv_CV
tags: arXiv_CV Optimization Deep_Learning Prediction
author: Alex Zihao Zhu, Wenxin Liu, Ziyun Wang, Vijay Kumar, Kostas Daniilidis
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we propose a method that combines unsupervised deep learning predictions for optical flow and monocular disparity with a model based optimization procedure for camera pose. Given the flow and disparity predictions from the network, we apply a RANSAC outlier rejection scheme to find an inlier set of flows and disparities, which we use to solve for the camera pose in a least squares fashion. We show that this pipeline is fully differentiable, allowing us to combine the pose with the network outputs as an additional unsupervised training loss to further refine the predicted flows and disparities. This method not only allows us to directly regress pose from the network outputs, but also automatically segments away pixels that do not fit the rigid scene assumptions that many unsupervised structure from motion methods apply, such as on independently moving objects. We evaluate our method on the KITTI dataset, and demonstrate state of the art results, even in the presence of challenging independently moving objects.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1812.08351](https://arxiv.org/abs/1812.08351)

##### PDF
[https://arxiv.org/pdf/1812.08351](https://arxiv.org/pdf/1812.08351)

