---
layout: post
title: "Image Smoothing via Unsupervised Learning"
date: 2018-11-07 09:08:05
categories: arXiv_CV
tags: arXiv_CV Regularization CNN
author: Qingnan Fan, Jiaolong Yang, David Wipf, Baoquan Chen, Xin Tong
mathjax: true
---

* content
{:toc}

##### Abstract
Image smoothing represents a fundamental component of many disparate computer vision and graphics applications. In this paper, we present a unified unsupervised (label-free) learning framework that facilitates generating flexible and high-quality smoothing effects by directly learning from data using deep convolutional neural networks (CNNs). The heart of the design is the training signal as a novel energy function that includes an edge-preserving regularizer which helps maintain important yet potentially vulnerable image structures, and a spatially-adaptive Lp flattening criterion which imposes different forms of regularization onto different image regions for better smoothing quality. We implement a diverse set of image smoothing solutions employing the unified framework targeting various applications such as, image abstraction, pencil sketching, detail enhancement, texture removal and content-aware image manipulation, and obtain results comparable with or better than previous methods. Moreover, our method is extremely fast with a modern GPU (e.g, 200 fps for 1280x720 images). Our codes and model are released in https://github.com/fqnchina/ImageSmoothing.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.02804](http://arxiv.org/abs/1811.02804)

##### PDF
[http://arxiv.org/pdf/1811.02804](http://arxiv.org/pdf/1811.02804)

