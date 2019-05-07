---
layout: post
title: "A Transfer-Learning Approach for Accelerated MRI using Deep Neural Networks"
date: 2019-05-04 09:43:36
categories: arXiv_CV
tags: arXiv_CV
author: Salman Ul Hassan Dar, Muzaffer &#xd6;zbey, Ahmet Burak &#xc7;atl&#x131;, Tolga &#xc7;ukur
mathjax: true
---

* content
{:toc}

##### Abstract
Purpose: Neural networks have received recent interest for reconstruction of undersampled MR acquisitions. Ideally network performance should be optimized by drawing the training and testing data from the same domain. In practice, however, large datasets comprising hundreds of subjects scanned under a common protocol are rare. The goal of this study is to introduce a transfer-learning approach to address the problem of data scarcity in training deep networks for accelerated MRI. 
 Methods: Neural networks were trained on thousands of samples from public datasets of either natural images or brain MR images. The networks were then fine-tuned using only few tens of brain MR images in a distinct testing domain. Domain-transferred networks were compared to networks trained directly in the testing domain. Network performance was evaluated for varying acceleration factors (2-10), number of training samples (0.5-4k) and number of fine-tuning samples (0-100). 
 Results: The proposed approach achieves successful domain transfer between MR images acquired with different contrasts (T1- and T2-weighted images), and between natural and MR images (ImageNet and T1- or T2-weighted images). Networks obtained via transfer-learning using only tens of images in the testing domain achieve nearly identical performance to networks trained directly in the testing domain using thousands of images. 
 Conclusion: The proposed approach might facilitate the use of neural networks for MRI reconstruction without the need for collection of extensive imaging datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1710.02615](http://arxiv.org/abs/1710.02615)

##### PDF
[http://arxiv.org/pdf/1710.02615](http://arxiv.org/pdf/1710.02615)

