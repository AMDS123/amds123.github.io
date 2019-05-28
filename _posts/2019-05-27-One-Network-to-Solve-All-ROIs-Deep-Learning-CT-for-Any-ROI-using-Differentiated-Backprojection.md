---
layout: post
title: "One Network to Solve All ROIs: Deep Learning CT for Any ROI using Differentiated Backprojection"
date: 2019-05-27 04:26:34
categories: arXiv_CV
tags: arXiv_CV Object_Detection Deep_Learning Detection
author: Yoseob Han, Jong Chul Ye
mathjax: true
---

* content
{:toc}

##### Abstract
Computed tomography for region-of-interest (ROI) reconstruction has advantages of reducing X-ray radiation dose and using a small detector. However, standard analytic reconstruction methods suffer from severe cupping artifacts, and existing model-based iterative reconstruction methods require extensive computations. Recently, we proposed a deep neural network to learn the cupping artifact, but the network is not well generalized for different ROIs due to the singularities in the corrupted images. Therefore, there is an increasing demand for a neural network that works well for any ROI sizes. In this paper, two types of neural networks are designed. The first type learns ROI size-specific cupping artifacts from the analytic reconstruction images, whereas the second type network is to learn to invert the finite Hilbert transform from the truncated differentiated backprojection (DBP) data. Their generalizability for any ROI sizes is then examined. Experimental results show that the new type of neural network significantly outperforms the existing iterative methods for any ROI size in spite of significantly reduced run-time complexity. Since the proposed method consistently surpasses existing methods for any ROIs, it can be used as a general CT reconstruction engine for many practical applications without compromising possible detector truncation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.00500](http://arxiv.org/abs/1810.00500)

##### PDF
[http://arxiv.org/pdf/1810.00500](http://arxiv.org/pdf/1810.00500)

