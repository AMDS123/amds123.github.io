---
layout: post
title: "Learning Object Bounding Boxes for 3D Instance Segmentation on Point Clouds"
date: 2019-06-04 00:33:56
categories: arXiv_AI
tags: arXiv_AI Segmentation Prediction
author: Bo Yang, Jianan Wang, Ronald Clark, Qingyong Hu, Sen Wang, Andrew Markham, Niki Trigoni
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel, conceptually simple and general framework for instance segmentation on 3D point clouds. Our method, called 3D-BoNet, follows the simple design philosophy of per-point multilayer perceptrons (MLPs). The framework directly regresses 3D bounding boxes for all instances in a point cloud, while simultaneously predicting a point-level mask for each instance. It consists of a backbone network followed by two parallel network branches for 1) bounding box regression and 2) point mask prediction. 3D-BoNet is single-stage, anchor-free and end-to-end trainable. Moreover, it is remarkably computationally efficient as, unlike existing approaches, it does not require any post-processing steps such as non-maximum suppression, feature sampling, clustering or voting. Extensive experiments show that our approach surpasses existing work on both ScanNet and S3DIS datasets while being approximately 10x more computationally efficient. Comprehensive ablation studies demonstrate the effectiveness of our design.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.01140](http://arxiv.org/abs/1906.01140)

##### PDF
[http://arxiv.org/pdf/1906.01140](http://arxiv.org/pdf/1906.01140)

