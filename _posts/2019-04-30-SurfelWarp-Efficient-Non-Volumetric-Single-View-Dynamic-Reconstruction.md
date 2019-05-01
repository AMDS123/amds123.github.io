---
layout: post
title: "SurfelWarp: Efficient Non-Volumetric Single View Dynamic Reconstruction"
date: 2019-04-30 06:57:53
categories: arXiv_CV
tags: arXiv_CV Tracking SLAM
author: Wei Gao, Russ Tedrake
mathjax: true
---

* content
{:toc}

##### Abstract
We contribute a dense SLAM system that takes a live stream of depth images as input and reconstructs non-rigid deforming scenes in real time, without templates or prior models. In contrast to existing approaches, we do not maintain any volumetric data structures, such as truncated signed distance function (TSDF) fields or deformation fields, which are performance and memory intensive. Our system works with a flat point (surfel) based representation of geometry, which can be directly acquired from commodity depth sensors. Standard graphics pipelines and general purpose GPU (GPGPU) computing are leveraged for all central operations: i.e., nearest neighbor maintenance, non-rigid deformation field estimation and fusion of depth measurements. Our pipeline inherently avoids expensive volumetric operations such as marching cubes, volumetric fusion and dense deformation field update, leading to significantly improved performance. Furthermore, the explicit and flexible surfel based geometry representation enables efficient tackling of topology changes and tracking failures, which makes our reconstructions consistent with updated depth observations. Our system allows robots to maintain a scene description with non-rigidly deformed objects that potentially enables interactions with dynamic working environments.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.13073](http://arxiv.org/abs/1904.13073)

##### PDF
[http://arxiv.org/pdf/1904.13073](http://arxiv.org/pdf/1904.13073)

