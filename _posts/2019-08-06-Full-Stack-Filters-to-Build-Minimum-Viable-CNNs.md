---
layout: post
title: "Full-Stack Filters to Build Minimum Viable CNNs"
date: 2019-08-06 08:55:47
categories: arXiv_CV
tags: arXiv_CV CNN Relation
author: Kai Han, Yunhe Wang, Yixing Xu, Chunjing Xu, Dacheng Tao, Chang Xu
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolutional neural networks (CNNs) are usually over-parameterized, which cannot be easily deployed on edge devices such as mobile phones and smart cameras. Existing works used to decrease the number or size of requested convolution filters for a minimum viable CNN on edge devices. In contrast, this paper introduces filters that are full-stack and can be used to generate many more sub-filters. Weights of these sub-filters are inherited from full-stack filters with the help of different binary masks. Orthogonal constraints are applied over binary masks to decrease their correlation and promote the diversity of generated sub-filters. To preserve the same volume of output feature maps, we can naturally reduce the number of established filters by only maintaining a few full-stack filters and a set of binary masks. We also conduct theoretical analysis on the memory cost and an efficient implementation is introduced for the convolution of the proposed filters. Experiments on several benchmark datasets and CNN models demonstrate that the proposed method is able to construct minimum viable convolution networks of comparable performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.02023](http://arxiv.org/abs/1908.02023)

##### PDF
[http://arxiv.org/pdf/1908.02023](http://arxiv.org/pdf/1908.02023)

