---
layout: post
title: "DPOD: 6D Pose Object Detector and Refiner"
date: 2019-04-08 17:45:36
categories: arXiv_CV
tags: arXiv_CV Object_Detection Pose_Estimation Deep_Learning Detection
author: Sergey Zakharov, Ivan Shugurov, Slobodan Ilic
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we present a novel deep learning method for 3D object detection and 6D pose estimation from RGB images. Our method, named DPOD (Dense Pose Object Detector), estimates dense multi-class 2D-3D correspondence maps between an input image and available 3D models. Given the correspondences, a 6DoF pose is computed via PnP and RANSAC. An additional RGB pose refinement of the initial pose estimates is performed using a custom deep learning based refinement scheme. Our results and comparison to a vast number of related works demonstrate that a large number of correspondences is beneficial for obtaining high quality 6D poses both before and after refinement. Unlike other methods that mainly use real data for training and do not train on synthetic renderings, we perform evaluation on both synthetic and real training data demonstrating superior results before and after refinement when compared to all recent detectors. While being precise, the presented approach is still real-time capable.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.11020](http://arxiv.org/abs/1902.11020)

##### PDF
[http://arxiv.org/pdf/1902.11020](http://arxiv.org/pdf/1902.11020)

