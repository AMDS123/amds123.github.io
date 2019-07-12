---
layout: post
title: "Extension of Sinkhorn Method: Optimal Movement Estimation of Agents Moving at Constant Velocity"
date: 2019-07-11 08:01:56
categories: arXiv_CV
tags: arXiv_CV Tracking Object_Tracking
author: Daigo Okada, Naotoshi Nakamura, Takuya Wada, Ayako Iwasaki, Ryo Yamada
mathjax: true
---

* content
{:toc}

##### Abstract
In the field of bioimaging, an important part of analyzing the motion of objects is tracking. We propose a method that applies the Sinkhorn distance for solving the optimal transport problem to track objects. The advantage of this method is that it can flexibly incorporate various assumptions in tracking as a cost matrix. First, we extend the Sinkhorn distance from two dimensions to three dimensions. Using this three-dimensional distance, we compare the performance of two types of tracking technique, namely tracking that associates objects that are close to each other, which conventionally uses the nearest-neighbor method, and tracking that assumes that the object is moving at constant velocity, using three types of simulation data. The results suggest that when tracking objects moving at constant velocity, our method is superior to conventional nearest-neighbor tracking as long as the added noise is not excessively large. We show that the Sinkhorn method can be applied effectively to object tracking. Our simulation data analysis suggests that when objects are moving at constant velocity, our method, which sets acceleration as a cost, outperforms the traditional nearest-neighbor method in terms of tracking objects. To apply the proposed method to real bioimaging data, it is necessary to set an appropriate cost indicator based on the movement features.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.05036](http://arxiv.org/abs/1907.05036)

##### PDF
[http://arxiv.org/pdf/1907.05036](http://arxiv.org/pdf/1907.05036)

