---
layout: post
title: "Learning 3D Shape Completion under Weak Supervision"
date: 2018-11-27 15:03:06
categories: arXiv_CV
tags: arXiv_CV Sparse Optimization
author: David Stutz, Andreas Geiger
mathjax: true
---

* content
{:toc}

##### Abstract
We address the problem of 3D shape completion from sparse and noisy point clouds, a fundamental problem in computer vision and robotics. Recent approaches are either data-driven or learning-based: Data-driven approaches rely on a shape model whose parameters are optimized to fit the observations; Learning-based approaches, in contrast, avoid the expensive optimization step by learning to directly predict complete shapes from incomplete observations in a fully-supervised setting. However, full supervision is often not available in practice. In this work, we propose a weakly-supervised learning-based approach to 3D shape completion which neither requires slow optimization nor direct supervision. While we also learn a shape prior on synthetic data, we amortize, i.e., learn, maximum likelihood fitting using deep neural networks resulting in efficient shape completion without sacrificing accuracy. On synthetic benchmarks based on ShapeNet and ModelNet as well as on real robotics data from KITTI and Kinect, we demonstrate that the proposed amortized maximum likelihood approach is able to compete with recent fully supervised baselines and outperforms data-driven approaches, while requiring less supervision and being significantly faster.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.07290](http://arxiv.org/abs/1805.07290)

##### PDF
[http://arxiv.org/pdf/1805.07290](http://arxiv.org/pdf/1805.07290)

