---
layout: post
title: "Joint Group Feature Selection and Discriminative Filter Learning for Robust Visual Object Tracking"
date: 2019-07-30 21:41:59
categories: arXiv_CV
tags: arXiv_CV Knowledge Tracking Object_Tracking Relation
author: Tianyang Xu, Zhen-Hua Feng, Xiao-Jun Wu, Josef Kittler
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new Group Feature Selection method for Discriminative Correlation Filters (GFS-DCF) based visual object tracking. The key innovation of the proposed method is to perform group feature selection across both channel and spatial dimensions, thus to pinpoint the structural relevance of multi-channel features to the filter system. In contrast to the widely used spatial regularisation or feature selection methods, to the best of our knowledge, this is the first time that channel selection has been advocated for DCF-based tracking. We demonstrate that our GFS-DCF method is able to significantly improve the performance of a DCF tracker equipped with deep neural network features. In addition, our GFS-DCF enables joint feature selection and filter learning, achieving enhanced discrimination and interpretability of the learned filters. 
 To further improve the performance, we adaptively integrate historical information by constraining filters to be smooth across temporal frames, using an efficient low-rank approximation. By design, specific temporal-spatial-channel configurations are dynamically learned in the tracking process, highlighting the relevant features, alleviating the performance degrading impact of less discriminative representations and reducing information redundancy. The experimental results obtained on OTB2013, OTB2015, VOT2017, VOT2018 and TrackingNet demonstrate the merits of our GFS-DCF and its superiority over the state-of-the-art trackers. The code is publicly available at https://github.com/XU-TIANYANG/GFS-DCF.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.13242](http://arxiv.org/abs/1907.13242)

##### PDF
[http://arxiv.org/pdf/1907.13242](http://arxiv.org/pdf/1907.13242)

