---
layout: post
title: "UprightNet: Geometry-Aware Camera Orientation Estimation from Single Images"
date: 2019-08-19 21:07:16
categories: arXiv_CV
tags: arXiv_CV Face Deep_Learning Prediction
author: Wenqi Xian, Zhengqi Li, Matthew Fisher, Jonathan Eisenmann, Eli Shechtman, Noah Snavely
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce UprightNet, a learning-based approach for estimating 2DoF camera orientation from a single RGB image of an indoor scene. Unlike recent methods that leverage deep learning to perform black-box regression from image to orientation parameters, we propose an end-to-end framework that incorporates explicit geometric reasoning. In particular, we design a network that predicts two representations of scene geometry, in both the local camera and global reference coordinate systems, and solves for the camera orientation as the rotation that best aligns these two predictions via a differentiable least squares module. This network can be trained end-to-end, and can be supervised with both ground truth camera poses and intermediate representations of surface geometry. We evaluate UprightNet on the single-image camera orientation task on synthetic and real datasets, and show significant improvements over prior state-of-the-art approaches.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.07070](http://arxiv.org/abs/1908.07070)

##### PDF
[http://arxiv.org/pdf/1908.07070](http://arxiv.org/pdf/1908.07070)

