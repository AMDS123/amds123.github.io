---
layout: post
title: "Segmentation of Levator Hiatus Using Multi-Scale Local Region Active contours and Boundary Shape Similarity Constraint"
date: 2019-01-11 04:15:09
categories: arXiv_CV
tags: arXiv_CV Segmentation Quantitative
author: Xinling Zhang, Xu Li, Ying Chen, Yixin Gan, Dexing Kong, Rongqin Zheng
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, a multi-scale framework with local region based active contour and boundary shape similarity constraint is proposed for the segmentation of levator hiatus in ultrasound images. In this paper, we proposed a multiscale active contour framework to segment levator hiatus ultrasound images by combining the local region information and boundary shape similarity constraint. In order to get more precisely initializations and reduce the computational cost, Gaussian pyramid method is used to decompose the image into coarse-to-fine scales. A localized region active contour model is firstly performed on the coarsest scale image to get a rough contour of the levator hiatus, then the segmentation result on the coarse scale is interpolated into the finer scale image as the initialization. The boundary shape similarity between different scales is incorporate into the local region based active contour model so that the result from coarse scale can guide the contour evolution at finer scale. By incorporating the multi-scale and boundary shape similarity, the proposed method can precisely locate the levator hiatus boundaries despite various ultrasound image artifacts. With a data set of 90 levator hiatus ultrasound images, the efficiency and accuracy of the proposed method are validated by quantitative and qualitative evaluations (TP, FP, Js) and comparison with other two state-of-art active contour segmentation methods (C-V model, DRLSE model).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.03472](http://arxiv.org/abs/1901.03472)

##### PDF
[http://arxiv.org/pdf/1901.03472](http://arxiv.org/pdf/1901.03472)

