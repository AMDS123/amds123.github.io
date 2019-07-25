---
layout: post
title: "Multi-adversarial Faster-RCNN for Unrestricted Object Detection"
date: 2019-07-24 10:12:36
categories: arXiv_CV
tags: arXiv_CV Adversarial Object_Detection Knowledge Detection
author: Zhenwei He, Lei Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Conventional object detection methods essentially suppose that the training and testing data are collected from a restricted target domain with expensive labeling cost. For alleviating the problem of domain dependency and cumbersome labeling, this paper proposes to detect objects in unrestricted environment by leveraging domain knowledge trained from an auxiliary source domain with sufficient labels. Specifically, we propose a multi-adversarial Faster-RCNN (MAF) framework for unrestricted object detection, which inherently addresses domain disparity minimization for domain adaptation in feature representation. The paper merits are in three-fold: 1) With the idea that object detectors often becomes domain incompatible when image distribution resulted domain disparity appears, we propose a hierarchical domain feature alignment module, in which multiple adversarial domain classifier submodules for layer-wise domain feature confusion are designed; 2) An information invariant scale reduction module (SRM) for hierarchical feature map resizing is proposed for promoting the training efficiency of adversarial domain adaptation; 3) In order to improve the domain adaptability, the aggregated proposal features with detection results are feed into a proposed weighted gradient reversal layer (WGRL) for characterizing hard confused domain samples. We evaluate our MAF on unrestricted tasks including Cityscapes, KITTI, Sim10k, etc. and the experiments show the state-of-the-art performance over the existing detectors.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.10343](http://arxiv.org/abs/1907.10343)

##### PDF
[http://arxiv.org/pdf/1907.10343](http://arxiv.org/pdf/1907.10343)

