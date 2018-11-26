---
layout: post
title: "Supervised Fitting of Geometric Primitives to 3D Point Clouds"
date: 2018-11-22 01:45:54
categories: arXiv_CV
tags: arXiv_CV Face Prediction
author: Lingxiao Li, Minhyuk Sung, Anastasia Dubrovina, Li Yi, Leonidas Guibas
mathjax: true
---

* content
{:toc}

##### Abstract
Fitting geometric primitives to 3D point cloud data bridges a gap between low-level digitized 3D data and high-level structural information on the underlying 3D shapes. As such, it enables many downstream applications in 3D data processing. For a long time, RANSAC-based methods have been the gold standard for such primitive fitting problems, but they require careful per-input parameter tuning and thus do not scale well for large datasets with diverse shapes. In this work, we introduce Supervised Primitive Fitting Network (SPFN), an end-to-end neural network that can robustly detect a varying number of primitives at different scales without any user control. The network is supervised using ground truth primitive surfaces and primitive membership for the input points. Instead of directly predicting the primitives, our architecture first predicts per-point properties and then uses a differential model estimation module to compute the primitive type and parameters. We evaluate our approach on a novel benchmark of ANSI 3D mechanical component models and demonstrate a significant improvement over both the state-of-the-art RANSAC-based methods and the direct neural prediction.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.08988](http://arxiv.org/abs/1811.08988)

##### PDF
[http://arxiv.org/pdf/1811.08988](http://arxiv.org/pdf/1811.08988)

