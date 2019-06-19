---
layout: post
title: "Active Scene Understanding via Online Semantic Reconstruction"
date: 2019-06-18 07:15:27
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Recognition
author: Lintao Zheng, Chenyang Zhu, Jiazhao Zhang, Hang Zhao, Hui Huang, Matthias Niessner, Kai Xu
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel approach to robot-operated active understanding of unknown indoor scenes, based on online RGBD reconstruction with semantic segmentation. In our method, the exploratory robot scanning is both driven by and targeting at the recognition and segmentation of semantic objects from the scene. Our algorithm is built on top of the volumetric depth fusion framework (e.g., KinectFusion) and performs real-time voxel-based semantic labeling over the online reconstructed volume. The robot is guided by an online estimated discrete viewing score field (VSF) parameterized over the 3D space of 2D location and azimuth rotation. VSF stores for each grid the score of the corresponding view, which measures how much it reduces the uncertainty (entropy) of both geometric reconstruction and semantic labeling. Based on VSF, we select the next best views (NBV) as the target for each time step. We then jointly optimize the traverse path and camera trajectory between two adjacent NBVs, through maximizing the integral viewing score (information gain) along path and trajectory. Through extensive evaluation, we show that our method achieves efficient and accurate online scene parsing during exploratory scanning.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.07409](http://arxiv.org/abs/1906.07409)

##### PDF
[http://arxiv.org/pdf/1906.07409](http://arxiv.org/pdf/1906.07409)

