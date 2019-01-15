---
layout: post
title: "Fast and Robust Multi-Person 3D Pose Estimation from Multiple Views"
date: 2019-01-14 03:27:05
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Optimization Prediction Detection
author: Junting Dong, Wen Jiang, Qixing Huang, Hujun Bao, Xiaowei Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the problem of 3D pose estimation for multiple people in a few calibrated camera views. The main challenge of this problem is to find the cross-view correspondences among noisy and incomplete 2D pose predictions. Most previous methods address this challenge by directly reasoning in 3D using a pictorial structure model, which is inefficient due to the huge state space. We propose a fast and robust approach to solve this problem. Our key idea is to use a multi-way matching algorithm to cluster the detected 2D poses in all views. Each resulting cluster encodes 2D poses of the same person across different views and consistent correspondences across the keypoints, from which the 3D pose of each person can be effectively inferred. The proposed convex optimization based multi-way matching algorithm is efficient and robust against missing and false detections, without knowing the number of people in the scene. Moreover, we propose to combine geometric and appearance cues for cross-view matching. The proposed approach achieves significant performance gains from the state-of-the-art (96.3% vs. 90.6% and 96.9% vs. 88% on the Campus and Shelf datasets, respectively), while being efficient for real-time applications.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.04111](http://arxiv.org/abs/1901.04111)

##### PDF
[http://arxiv.org/pdf/1901.04111](http://arxiv.org/pdf/1901.04111)

