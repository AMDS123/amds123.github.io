---
layout: post
title: "STD: Sparse-to-Dense 3D Object Detector for Point Cloud"
date: 2019-07-22 16:20:44
categories: arXiv_CV
tags: arXiv_CV Object_Detection Sparse Inference Prediction Detection
author: Zetong Yang, Yanan Sun, Shu Liu, Xiaoyong Shen, Jiaya Jia
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new two-stage 3D object detection framework, named sparse-to-dense 3D Object Detector (STD). The first stage is a bottom-up proposal generation network that uses raw point cloud as input to generate accurate proposals by seeding each point with a new spherical anchor. It achieves a high recall with less computation compared with prior works. Then, PointsPool is applied for generating proposal features by transforming their interior point features from sparse expression to compact representation, which saves even more computation time. In box prediction, which is the second stage, we implement a parallel intersection-over-union (IoU) branch to increase awareness of localization accuracy, resulting in further improved performance. We conduct experiments on KITTI dataset, and evaluate our method in terms of 3D object and Bird's Eye View (BEV) detection. Our method outperforms other state-of-the-arts by a large margin, especially on the hard set, with inference speed more than 10 FPS.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.10471](http://arxiv.org/abs/1907.10471)

##### PDF
[http://arxiv.org/pdf/1907.10471](http://arxiv.org/pdf/1907.10471)

