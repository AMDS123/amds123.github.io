---
layout: post
title: "RGB-based 3D Hand Pose Estimation via Privileged Learning with Depth Images"
date: 2018-11-18 18:52:08
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Prediction
author: Shanxin Yuan, Bjorn Stenger, Tae-Kyun Kim
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a method for hand pose estimation from RGB images that uses both external large-scale depth image datasets and paired depth and RGB images as privileged information at training time. We show that providing depth information during training significantly improves performance of pose estimation from RGB images during testing. We explore different ways of using this privileged information: (1) using depth data to initially train a depth-based network, (2) using the features from the depth-based network of the paired depth images to constrain mid-level RGB network weights, and (3) using the foreground mask, obtained from the depth data, to suppress the responses from the background area. By using paired RGB and depth images, we are able to supervise the RGB-based network to learn middle layer features that mimic that of the corresponding depth-based network, which is trained on large-scale, accurately annotated depth data. During testing, when only an RGB image is available, our method produces accurate 3D hand pose predictions. Our method is also tested on 2D hand pose estimation. Experiments on three public datasets show that the method outperforms the state-of-the-art methods for hand pose estimation using RGB image input.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.07376](http://arxiv.org/abs/1811.07376)

##### PDF
[http://arxiv.org/pdf/1811.07376](http://arxiv.org/pdf/1811.07376)

