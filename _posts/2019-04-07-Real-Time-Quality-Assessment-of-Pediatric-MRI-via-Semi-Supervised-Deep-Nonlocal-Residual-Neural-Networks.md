---
layout: post
title: "Real-Time Quality Assessment of Pediatric MRI via Semi-Supervised Deep Nonlocal Residual Neural Networks"
date: 2019-04-07 12:37:13
categories: arXiv_CV
tags: arXiv_CV QA
author: Siyuan Liu, Kim-Han Thung, Weili Lin, Pew-Thian Yap, Dinggang~Shen
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we introduce an image quality assessment (IQA) method for pediatric T1- and T2-weighted MR images. IQA is first performed slice-wise using a nonlocal residual neural network (NR-Net) and then volume-wise by agglomerating the slice QA results using random forest. Our method requires only a small amount of quality-annotated images for training and is designed to be robust to annotation noise that might occur due to rater errors and the inevitable mix of good and bad slices in an image volume. Using a small set of quality-assessed images, we pre-train NR-Net to annotate each image slice with an initial quality rating (i.e., pass, questionable, fail), which we then refine by semi-supervised learning and iterative self-training. Experimental results demonstrate that our method, trained using only samples of modest size, exhibit great generalizability, capable of real-time (milliseconds per volume) large-scale IQA with near-perfect accuracy.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.03639](http://arxiv.org/abs/1904.03639)

##### PDF
[http://arxiv.org/pdf/1904.03639](http://arxiv.org/pdf/1904.03639)

