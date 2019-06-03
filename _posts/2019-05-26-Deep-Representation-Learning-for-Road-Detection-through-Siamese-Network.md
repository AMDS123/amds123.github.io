---
layout: post
title: "Deep Representation Learning for Road Detection through Siamese Network"
date: 2019-05-26 19:44:10
categories: arXiv_CV
tags: arXiv_CV Represenation_Learning Deep_Learning Detection
author: Huafeng Liu, Xiaofeng Han, Xiangrui Li, Yazhou Yao, Pu Huang, Zhenming Tang
mathjax: true
---

* content
{:toc}

##### Abstract
Robust road detection is a key challenge in safe autonomous driving. Recently, with the rapid development of 3D sensors, more and more researchers are trying to fuse information across different sensors to improve the performance of road detection. Although many successful works have been achieved in this field, methods for data fusion under deep learning framework is still an open problem. In this paper, we propose a Siamese deep neural network based on FCN-8s to detect road region. Our method uses data collected from a monocular color camera and a Velodyne-64 LiDAR sensor. We project the LiDAR point clouds onto the image plane to generate LiDAR images and feed them into one of the branches of the network. The RGB images are fed into another branch of our proposed network. The feature maps that these two branches extract in multiple scales are fused before each pooling layer, via padding additional fusion layers. Extensive experimental results on public dataset KITTI ROAD demonstrate the effectiveness of our proposed approach.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.13394](http://arxiv.org/abs/1905.13394)

##### PDF
[http://arxiv.org/pdf/1905.13394](http://arxiv.org/pdf/1905.13394)

