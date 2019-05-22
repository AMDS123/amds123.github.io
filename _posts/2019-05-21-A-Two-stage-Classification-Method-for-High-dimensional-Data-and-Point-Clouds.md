---
layout: post
title: "A Two-stage Classification Method for High-dimensional Data and Point Clouds"
date: 2019-05-21 10:45:59
categories: arXiv_CV
tags: arXiv_CV Classification
author: Xiaohao Cai, Raymond Chan, Xiaoyu Xie, Tieyong Zeng
mathjax: true
---

* content
{:toc}

##### Abstract
High-dimensional data classification is a fundamental task in machine learning and imaging science. In this paper, we propose a two-stage multiphase semi-supervised classification method for classifying high-dimensional data and unstructured point clouds. To begin with, a fuzzy classification method such as the standard support vector machine is used to generate a warm initialization. We then apply a two-stage approach named SaT (smoothing and thresholding) to improve the classification. In the first stage, an unconstraint convex variational model is implemented to purify and smooth the initialization, followed by the second stage which is to project the smoothed partition obtained at stage one to a binary partition. These two stages can be repeated, with the latest result as a new initialization, to keep improving the classification quality. We show that the convex model of the smoothing stage has a unique solution and can be solved by a specifically designed primal-dual algorithm whose convergence is guaranteed. We test our method and compare it with the state-of-the-art methods on several benchmark data sets. The experimental results demonstrate clearly that our method is superior in both the classification accuracy and computation speed for high-dimensional data and point clouds.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.08538](http://arxiv.org/abs/1905.08538)

##### PDF
[http://arxiv.org/pdf/1905.08538](http://arxiv.org/pdf/1905.08538)

