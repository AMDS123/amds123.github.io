---
layout: post
title: "Non-destructive three-dimensional measurement of hand vein based on self-supervised network"
date: 2019-06-29 15:01:16
categories: arXiv_CV
tags: arXiv_CV
author: Xiaoyu Chen, Qixin Wang, Jinzhou Ge, Yi Zhang, Jing Han
mathjax: true
---

* content
{:toc}

##### Abstract
At present, supervised stereo methods based on deep neural network have achieved impressive results. However, in some scenarios, accurate three-dimensional labels are inaccessible for supervised training. In this paper, a self-supervised network is proposed for binocular disparity matching (SDMNet), which computes dense disparity maps from stereo image pairs without disparity labels: In the self-supervised training, we match the stereo images densely to approximate the disparity maps and use them to warp the left and right images to estimate the right and left images; we build the loss function between estimated images and original images for self-supervised training, which adopts perceptual loss to help improve the quality of disparity maps in both detail and structure. Then, we use SDMNet to obtain disparities of hand vein. SDMNet has achieved excellent results on KITTI 2012, KITTI 2015, simulated vein dataset and real vein dataset, outperforming many state-of-the-art supervised matching methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.00215](http://arxiv.org/abs/1907.00215)

##### PDF
[http://arxiv.org/pdf/1907.00215](http://arxiv.org/pdf/1907.00215)

