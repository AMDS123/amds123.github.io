---
layout: post
title: "Cascaded Parallel Filtering for Memory-Efficient Image-Based Localization"
date: 2019-08-16 19:39:17
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation
author: Wentao Cheng, Weisi Lin, Kan Chen, Xinfeng Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Image-based localization (IBL) aims to estimate the 6DOF camera pose for a given query image. The camera pose can be computed from 2D-3D matches between a query image and Structure-from-Motion (SfM) models. Despite recent advances in IBL, it remains difficult to simultaneously resolve the memory consumption and match ambiguity problems of large SfM models. In this work, we propose a cascaded parallel filtering method that leverages the feature, visibility and geometry information to filter wrong matches under binary feature representation. The core idea is that we divide the challenging filtering task into two parallel tasks before deriving an auxiliary camera pose for final filtering. One task focuses on preserving potentially correct matches, while another focuses on obtaining high quality matches to facilitate subsequent more powerful filtering. Moreover, our proposed method improves the localization accuracy by introducing a quality-aware spatial reconfiguration method and a principal focal length enhanced pose estimation method. Experimental results on real-world datasets demonstrate that our method achieves very competitive localization performances in a memory-efficient manner.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.06141](http://arxiv.org/abs/1908.06141)

##### PDF
[http://arxiv.org/pdf/1908.06141](http://arxiv.org/pdf/1908.06141)

