---
layout: post
title: "Justlookup: One Millisecond Deep Feature Extraction for Point Clouds By Lookup Tables"
date: 2019-08-14 07:07:26
categories: arXiv_CV
tags: arXiv_CV Inference
author: Hongxin Lin, Zelin Xiao, Yang Tan, Hongyang Chao, Shengyong Ding
mathjax: true
---

* content
{:toc}

##### Abstract
Deep models are capable of fitting complex high dimensional functions while usually yielding large computation load. There is no way to speed up the inference process by classical lookup tables due to the high-dimensional input and limited memory size. Recently, a novel architecture (PointNet) for point clouds has demonstrated that it is possible to obtain a complicated deep function from a set of 3-variable functions. In this paper, we exploit this property and apply a lookup table to encode these 3-variable functions. This method ensures that the inference time is only determined by the memory access no matter how complicated the deep function is. We conduct extensive experiments on ModelNet and ShapeNet datasets and demonstrate that we can complete the inference process in 1.5 ms on an Intel i7-8700 CPU (single core mode), 32x speedup over the PointNet architecture without any performance degradation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.08996](http://arxiv.org/abs/1908.08996)

##### PDF
[http://arxiv.org/pdf/1908.08996](http://arxiv.org/pdf/1908.08996)

