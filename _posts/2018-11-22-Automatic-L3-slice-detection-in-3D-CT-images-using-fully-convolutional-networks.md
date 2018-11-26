---
layout: post
title: "Automatic L3 slice detection in 3D CT images using fully-convolutional networks"
date: 2018-11-22 17:31:18
categories: arXiv_AI
tags: arXiv_AI CNN Prediction Quantitative Detection
author: Fahdi Kanavati, Shah Islam, Eric O. Aboagye, Andrea Rockall
mathjax: true
---

* content
{:toc}

##### Abstract
The analysis of single CT slices extracted at the third lumbar vertebra (L3) has garnered significant clinical interest in the past few years, in particular in regards to quantifying sarcopenia (muscle loss). In this paper, we propose an efficient method to automatically detect the L3 slice in 3D CT images. Our method works with images with a variety of fields of view, occlusions, and slice thicknesses. 3D CT images are first converted into 2D via Maximal Intensity Projection (MIP), reducing the dimensionality of the problem. The MIP images are then used as input to a 2D fully-convolutional network to predict the L3 slice locations in the form of 2D confidence maps. In addition we propose a variant architecture with less parameters allowing 1D confidence map prediction and slightly faster prediction time without loss of accuracy. Quantitative evaluation of our method on a dataset of 1006 3D CT images yields a median error of 1mm, similar to the inter-rater median error of 1mm obtained from two annotators, demonstrating the effectiveness of our method in efficiently and accurately detecting the L3 slice.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.09244](http://arxiv.org/abs/1811.09244)

##### PDF
[http://arxiv.org/pdf/1811.09244](http://arxiv.org/pdf/1811.09244)

