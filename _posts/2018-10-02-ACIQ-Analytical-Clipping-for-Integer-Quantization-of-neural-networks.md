---
layout: post
title: "ACIQ: Analytical Clipping for Integer Quantization of neural networks"
date: 2018-10-02 15:10:44
categories: arXiv_CV
tags: arXiv_CV Inference
author: Ron Banner, Yury Nahshan, Elad Hoffer, Daniel Soudry
mathjax: true
---

* content
{:toc}

##### Abstract
Unlike traditional approaches that focus on the quantization at the network level, in this work we propose to minimize the quantization effect at the tensor level. We analyze the trade-off between quantization noise and clipping distortion in low precision networks. We identify the statistics of various tensors, and derive exact expressions for the mean-square-error degradation due to clipping. By optimizing these expressions, we show marked improvements over standard quantization schemes that normally avoid clipping. For example, just by choosing the accurate clipping values, more than 40\% accuracy improvement is obtained for the quantization of VGG16-BN to 4-bits of precision. Our results have many applications for the quantization of neural networks at both training and inference time. One immediate application is for a rapid deployment of neural networks to low-precision accelerators without time-consuming fine tuning or the availability of the full datasets.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.05723](https://arxiv.org/abs/1810.05723)

##### PDF
[https://arxiv.org/pdf/1810.05723](https://arxiv.org/pdf/1810.05723)

