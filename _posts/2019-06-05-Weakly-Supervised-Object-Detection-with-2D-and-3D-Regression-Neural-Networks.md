---
layout: post
title: "Weakly Supervised Object Detection with 2D and 3D Regression Neural Networks"
date: 2019-06-05 09:08:38
categories: arXiv_CV
tags: arXiv_CV Object_Detection Attention Weakly_Supervised Deep_Learning Detection
author: Florian Dubost, Hieab Adams, Pinar Yilmaz, Gerda Bortsova, Gijs van Tulder, M. Arfan Ikram, Wiro Niessen, Meike Vernooij, Marleen de Bruijne
mathjax: true
---

* content
{:toc}

##### Abstract
Weakly supervised detection methods can infer the location of target objects in an image without requiring location or appearance information during training. We propose a weakly supervised deep learning method for the detection of objects that appear at multiple locations in an image. The method computes attention maps using the last feature maps of an encoder-decoder network optimized only with global labels: the number of occurrences of the target object in an image. In contrast with previous approaches, attention maps are generated at full input resolution thanks to the decoder part. The proposed approach is compared to multiple state-of-the-art methods in two tasks: the detection of digits in MNIST-based datasets, and the real life application of detection of enlarged perivascular spaces -- a type of brain lesion -- in four brain regions in a dataset of 2202 3D brain MRI scans. In MNIST-based datasets, the proposed method outperforms the other methods. In the brain dataset, several weakly supervised detection methods come close to the human intrarater agreement in each region. The proposed method reaches the lowest number of false positive detections in all brain regions at the operating point, while its average sensitivity is similar to that of the other best methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.01891](http://arxiv.org/abs/1906.01891)

##### PDF
[http://arxiv.org/pdf/1906.01891](http://arxiv.org/pdf/1906.01891)

