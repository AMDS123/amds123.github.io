---
layout: post
title: "Estimating 6D Pose From Localizing Designated Surface Keypoints"
date: 2018-12-04 12:55:06
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face Pose_Estimation Prediction Detection Relation
author: Zelin Zhao, Gao Peng, Haoyu Wang, Hao-Shu Fang, Chengkun Li, Cewu Lu
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present an accurate yet effective solution for 6D pose estimation from an RGB image. The core of our approach is that we first designate a set of surface points on target object model as keypoints and then train a keypoint detector (KPD) to localize them. Finally a PnP algorithm can recover the 6D pose according to the 2D-3D relationship of keypoints. Different from recent state-of-the-art CNN-based approaches that rely on a time-consuming post-processing procedure, our method can achieve competitive accuracy without any refinement after pose prediction. Meanwhile, we obtain a 30% relative improvement in terms of ADD accuracy among methods without using refinement. Moreover, we succeed in handling heavy occlusion by selecting the most confident keypoints to recover the 6D pose. For the sake of reproducibility, we will make our code and models publicly available soon.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.01387](http://arxiv.org/abs/1812.01387)

##### PDF
[http://arxiv.org/pdf/1812.01387](http://arxiv.org/pdf/1812.01387)

