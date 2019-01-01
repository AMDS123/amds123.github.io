---
layout: post
title: "PVNet: Pixel-wise Voting Network for 6DoF Pose Estimation"
date: 2018-12-31 13:24:10
categories: arXiv_CV
tags: arXiv_CV Sparse Pose_Estimation
author: Sida Peng, Yuan Liu, Qixing Huang, Hujun Bao, Xiaowei Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the challenge of 6DoF pose estimation from a single RGB image under severe occlusion or truncation. Many recent works have shown that a two-stage approach, which first detects keypoints and then solves a Perspective-n-Point (PnP) problem for pose estimation, achieves remarkable performance. However, most of these methods only localize a set of sparse keypoints by regressing their image coordinates or heatmaps, which are sensitive to occlusion and truncation. Instead, we introduce a Pixel-wise Voting Network (PVNet) to regress pixel-wise unit vectors pointing to the keypoints and use these vectors to vote for keypoint locations using RANSAC. This creates a flexible representation for localizing occluded or truncated keypoints. Another important feature of this representation is that it provides uncertainties of keypoint locations that can be further leveraged by the PnP solver. Experiments show that the proposed approach outperforms the state of the art on the LINEMOD, Occlusion LINEMOD and YCB-Video datasets by a large margin, while being efficient for real-time pose estimation. We further create a Truncation LINEMOD dataset to validate the robustness of our approach against truncation. The code will be avaliable at https://zju-3dv.github.io/pvnet/.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.11788](http://arxiv.org/abs/1812.11788)

##### PDF
[http://arxiv.org/pdf/1812.11788](http://arxiv.org/pdf/1812.11788)

