---
layout: post
title: "PointPillars: Fast Encoders for Object Detection from Point Clouds"
date: 2018-12-14 05:15:08
categories: arXiv_CV
tags: arXiv_CV Object_Detection GAN CNN Detection
author: Alex H. Lang, Sourabh Vora, Holger Caesar, Lubing Zhou, Jiong Yang, Oscar Beijbom
mathjax: true
---

* content
{:toc}

##### Abstract
Object detection in point clouds is an important aspect of many robotics applications such as autonomous driving. In this paper we consider the problem of encoding a point cloud into a format appropriate for a downstream detection pipeline. Recent literature suggests two types of encoders; fixed encoders tend to be fast but sacrifice accuracy, while encoders that are learned from data are more accurate, but slower. In this work we propose PointPillars, a novel encoder which utilizes PointNets to learn a representation of point clouds organized in vertical columns (pillars). While the encoded features can be used with any standard 2D convolutional detection architecture, we further propose a lean downstream network. Extensive experimentation shows that PointPillars outperforms previous encoders with respect to both speed and accuracy by a large margin. Despite only using lidar, our full detection pipeline significantly outperforms the state of the art, even among fusion methods, with respect to both the 3D and bird's eye view KITTI benchmarks. This detection performance is achieved while running at 62 Hz: a 2 - 4 fold runtime improvement. A faster version of our method matches the state of the art at 105 Hz. These benchmarks suggest that PointPillars is an appropriate encoding for object detection in point clouds.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.05784](http://arxiv.org/abs/1812.05784)

##### PDF
[http://arxiv.org/pdf/1812.05784](http://arxiv.org/pdf/1812.05784)

