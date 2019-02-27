---
layout: post
title: "RepNet: Weakly Supervised Training of an Adversarial Reprojection Network for 3D Human Pose Estimation"
date: 2019-02-26 11:23:54
categories: arXiv_CV
tags: arXiv_CV Adversarial Weakly_Supervised Pose_Estimation
author: Bastian Wandt, Bodo Rosenhahn
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the problem of 3D human pose estimation from single images. While for a long time human skeletons were parameterized and fitted to the observation by satisfying a reprojection error, nowadays researchers directly use neural networks to infer the 3D pose from the observations. However, most of these approaches ignore the fact that a reprojection constraint has to be satisfied and are sensitive to overfitting. We tackle the overfitting problem by ignoring 2D to 3D correspondences. This efficiently avoids a simple memorization of the training data and allows for a weakly supervised training. One part of the proposed reprojection network (RepNet) learns a mapping from a distribution of 2D poses to a distribution of 3D poses using an adversarial training approach. Another part of the network estimates the camera. This allows for the definition of a network layer that performs the reprojection of the estimated 3D pose back to 2D which results in a reprojection loss function. Our experiments show that RepNet generalizes well to unknown data and outperforms state-of-the-art methods when applied to unseen data. Moreover, our implementation runs in real-time on a standard desktop PC.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.09868](http://arxiv.org/abs/1902.09868)

##### PDF
[http://arxiv.org/pdf/1902.09868](http://arxiv.org/pdf/1902.09868)

