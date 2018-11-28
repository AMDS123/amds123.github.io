---
layout: post
title: "GarNet: A Two-stream Network for Fast and Accurate 3D Cloth Draping"
date: 2018-11-27 13:55:01
categories: arXiv_CV
tags: arXiv_CV Inference
author: Erhan Gundogdu, Victor Constantin, Amrollah Seifoddini, Minh Dang, Mathieu Salzmann, Pascal Fua
mathjax: true
---

* content
{:toc}

##### Abstract
While Physics-Based Simulation (PBS) can highly accurately drape a 3D garment model on a 3D body, it remains too costly for real-time applications, such as virtual try-on. By contrast, inference in a deep network, that is, a single forward pass, is typically quite fast. In this paper, we leverage this property and introduce a novel architecture to fit a 3D garment template to a 3D body model. Specifically, we build upon the recent progress in 3D point-cloud processing with deep networks to extract garment features at varying levels of detail, including point-wise, patch-wise and global features. We then fuse these features with those extracted in parallel from the 3D body, so as to model the cloth-body interactions. The resulting two-stream architecture is trained with a loss function inspired by physics-based modeling, and delivers realistic garment shapes whose 3D points are, on average, less than 1.5cm away from those of a PBS method, while running 40 times faster.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.10983](http://arxiv.org/abs/1811.10983)

##### PDF
[http://arxiv.org/pdf/1811.10983](http://arxiv.org/pdf/1811.10983)

