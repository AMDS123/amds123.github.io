---
layout: post
title: "3D Local Features for Direct Pairwise Registration"
date: 2019-04-08 18:17:36
categories: arXiv_AI
tags: arXiv_AI Pose_Estimation Prediction Quantitative
author: Haowen Deng, Tolga Birdal, Slobodan Ilic
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel, data driven approach for solving the problem of registration of two point cloud scans. Our approach is direct in the sense that a single pair of corresponding local patches already provides the necessary transformation cue for the global registration. To achieve that, we first endow the state of the art PPF-FoldNet auto-encoder (AE) with a pose-variant sibling, where the discrepancy between the two leads to pose-specific descriptors. Based upon this, we introduce RelativeNet, a relative pose estimation network to assign correspondence-specific orientations to the keypoints, eliminating any local reference frame computations. Finally, we devise a simple yet effective hypothesize-and-verify algorithm to quickly use the predictions and align two point sets. Our extensive quantitative and qualitative experiments suggests that our approach outperforms the state of the art in challenging real datasets of pairwise registration and that augmenting the keypoints with local pose information leads to better generalization and a dramatic speed-up.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.04281](http://arxiv.org/abs/1904.04281)

##### PDF
[http://arxiv.org/pdf/1904.04281](http://arxiv.org/pdf/1904.04281)

