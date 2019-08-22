---
layout: post
title: "GarNet: A Two-Stream Network for Fast and Accurate 3D Cloth Draping"
date: 2019-08-21 13:07:58
categories: arXiv_CV
tags: arXiv_CV Inference
author: Erhan Gundogdu, Victor Constantin, Amrollah Seifoddini, Minh Dang, Mathieu Salzmann, Pascal Fua
mathjax: true
---

* content
{:toc}

##### Abstract
While Physics-Based Simulation (PBS) can accurately drape a 3D garment on a 3D body, it remains too costly for real-time applications, such as virtual try-on. By contrast, inference in a deep network, requiring a single forward pass, is much faster. Taking advantage of this, we propose a novel architecture to fit a 3D garment template to a 3D body. Specifically, we build upon the recent progress in 3D point cloud processing with deep networks to extract garment features at varying levels of detail, including point-wise, patch-wise and global features. We fuse these features with those extracted in parallel from the 3D body, so as to model the cloth-body interactions. The resulting two-stream architecture, which we call as GarNet, is trained using a loss function inspired by physics-based modeling, and delivers visually plausible garment shapes whose 3D points are, on average, less than 1 cm away from those of a PBS method, while running 100 times faster. Moreover, the proposed method can model various garment types with different cutting patterns when parameters of those patterns are given as input to the network.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.10983](http://arxiv.org/abs/1811.10983)

##### PDF
[http://arxiv.org/pdf/1811.10983](http://arxiv.org/pdf/1811.10983)

