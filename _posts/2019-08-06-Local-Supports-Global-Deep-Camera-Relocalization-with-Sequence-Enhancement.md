---
layout: post
title: "Local Supports Global: Deep Camera Relocalization with Sequence Enhancement"
date: 2019-08-06 03:49:52
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation
author: Fei Xue, Xin Wang, Zike Yan, Qiuyuan Wang, Junqiu Wang, Hongbin Zha
mathjax: true
---

* content
{:toc}

##### Abstract
We propose to leverage the local information in image sequences to support global camera relocalization. In contrast to previous methods that regress global poses from single images, we exploit the spatial-temporal consistency in sequential images to alleviate uncertainty due to visual ambiguities by incorporating a visual odometry (VO) component. Specifically, we introduce two effective steps called content-augmented pose estimation and motion-based refinement. The content-augmentation step focuses on alleviating the uncertainty of pose estimation by augmenting the observation based on the co-visibility in local maps built by the VO stream. Besides, the motion-based refinement is formulated as a pose graph, where the camera poses are further optimized by adopting relative poses provided by the VO component as additional motion constraints. Thus, the global consistency can be guaranteed. Experiments on the public indoor 7-Scenes and outdoor Oxford RobotCar benchmark datasets demonstrate that benefited from local information inherent in the sequence, our approach outperforms state-of-the-art methods, especially in some challenging cases, e.g., insufficient texture, highly repetitive textures, similar appearances, and over-exposure.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.04391](http://arxiv.org/abs/1908.04391)

##### PDF
[http://arxiv.org/pdf/1908.04391](http://arxiv.org/pdf/1908.04391)

