---
layout: post
title: "Knowing what you know in brain segmentation using Bayesian deep neural networks"
date: 2019-06-16 20:50:59
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention Prediction
author: Patrick McClure, Nao Rho, John A. Lee, Jakub R. Kaczmarzyk, Charles Zheng, Satrajit S. Ghosh, Dylan Nielson, Adam G. Thomas, Peter Bandettini, Francisco Pereira
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we describe a deep neural network for predicting FreeSurfer segmentations of structural MRI volumes, in seconds rather than hours. The network was trained and evaluated on an extremely large dataset (n = 11,148), obtained by combining data from more than a hundred sites. We also show that the prediction uncertainty of the network at each voxel is a good indicator of whether the network has made an error. The resulting uncertainty volume can be used in conjunction with the predicted segmentation to improve downstream uses. These include the calculation of measures derived from segmentation regions of interest, easing the process of manual annotation by providing both a starting segmentation and an indication of where human attention is required, or the building of prediction models, among many others. We also demonstrate that the average prediction uncertainty across voxels in the brain is an excellent indicator of manual quality control ratings, outperforming a recently published method that combines a wide range of automated QC algorithms. Finally, we show that a Bayesian deep neural network trained using spike-and-slab dropout with learned model uncertainty improves both the segmentation performance and the usefulness of prediction uncertainties. The key results of this paper are general, and should apply to any new network architecture for addressing the segmentation problem.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.01719](http://arxiv.org/abs/1812.01719)

##### PDF
[http://arxiv.org/pdf/1812.01719](http://arxiv.org/pdf/1812.01719)

