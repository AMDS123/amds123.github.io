---
layout: post
title: "Part-level Car Parsing and Reconstruction from Single Street View"
date: 2019-08-26 14:46:00
categories: arXiv_CV
tags: arXiv_CV Segmentation Pose_Estimation
author: Qichuan Geng, Hong Zhang, Xinyu Huang, Sen Wang, Feixiang Lu, Xinjing Cheng, Zhong Zhou, Ruigang Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Part information has been shown to be resistant to occlusions and viewpoint changes, which is beneficial for various vision-related tasks. However, we found very limited work in car pose estimation and reconstruction from street views leveraging the part information. There are two major contributions in this paper. Firstly, we make the first attempt to build a framework to simultaneously estimate shape, translation, orientation, and semantic parts of cars in 3D space from a single street view. As it is labor-intensive to annotate semantic parts on real street views, we propose a specific approach to implicitly transfer part features from synthesized images to real street views. For pose and shape estimation, we propose a novel network structure that utilizes both part features and 3D losses. Secondly, we are the first to construct a high-quality dataset that contains 348 different car models with physical dimensions and part-level annotations based on global and local deformations. Given these models, we further generate 60K synthesized images with randomization of orientation, illumination, occlusion, and texture. Our results demonstrate that our part segmentation performance is significantly improved after applying our implicit transfer approach. Our network for pose and shape estimation achieves the state-of-the-art performance on the ApolloCar3D dataset and outperforms 3D-RCNN and DeepMANTA by 12.57 and 8.91 percentage points in terms of mean A3DP-Abs.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.10837](http://arxiv.org/abs/1811.10837)

##### PDF
[http://arxiv.org/pdf/1811.10837](http://arxiv.org/pdf/1811.10837)

