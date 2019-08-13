---
layout: post
title: "Dynamic Region Division for Adaptive Learning Pedestrian Counting"
date: 2019-08-12 01:17:50
categories: arXiv_CV
tags: arXiv_CV CNN
author: Gaoqi He, Zhenwei Ma, Binhao Huang, Bin Sheng, Yubo Yuan
mathjax: true
---

* content
{:toc}

##### Abstract
Accurate pedestrian counting algorithm is critical to eliminate insecurity in the congested public scenes. However, counting pedestrians in crowded scenes often suffer from severe perspective distortion. In this paper, basing on the straight-line double region pedestrian counting method, we propose a dynamic region division algorithm to keep the completeness of counting objects. Utilizing the object bounding boxes obtained by YoloV3 and expectation division line of the scene, the boundary for nearby region and distant one is generated under the premise of retaining whole head. Ulteriorly, appropriate learning models are applied to count pedestrians in each obtained region. In the distant region, a novel inception dilated convolutional neural network is proposed to solve the problem of choosing dilation rate. In the nearby region, YoloV3 is used for detecting the pedestrian in multi-scale. Accordingly, the total number of pedestrians in each frame is obtained by fusing the result in nearby and distant regions. A typical subway pedestrian video dataset is chosen to conduct experiment in this paper. The result demonstrate that proposed algorithm is superior to existing machine learning based methods in general performance.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.03978](https://arxiv.org/abs/1908.03978)

##### PDF
[https://arxiv.org/pdf/1908.03978](https://arxiv.org/pdf/1908.03978)

