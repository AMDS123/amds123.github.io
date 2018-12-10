---
layout: post
title: "Kernel Transformer Networks for Compact Spherical Convolution"
date: 2018-12-07 17:26:28
categories: arXiv_CV
tags: arXiv_CV CNN Recognition
author: Yu-Chuan Su, Kristen Grauman
mathjax: true
---

* content
{:toc}

##### Abstract
Ideally, 360{\deg} imagery could inherit the deep convolutional neural networks (CNNs) already trained with great success on perspective projection images. However, existing methods to transfer CNNs from perspective to spherical images introduce significant computational costs and/or degradations in accuracy. In this work, we present the Kernel Transformer Network (KTN). KTNs efficiently transfer convolution kernels from perspective images to the equirectangular projection of 360{\deg} images. Given a source CNN for perspective images as input, the KTN produces a function parameterized by a polar angle and kernel as output. Given a novel 360{\deg} image, that function in turn can compute convolutions for arbitrary layers and kernels as would the source CNN on the corresponding tangent plane projections. Distinct from all existing methods, KTNs allow model transfer: the same model can be applied to different source CNNs with the same base architecture. This enables application to multiple recognition tasks without re-training the KTN. Validating our approach with multiple source CNNs and datasets, we show that KTNs improve the state of the art for spherical convolution. KTNs successfully preserve the source CNN's accuracy, while offering transferability, scalability to typical image resolutions, and, in many cases, a substantially lower memory footprint.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.03115](http://arxiv.org/abs/1812.03115)

##### PDF
[http://arxiv.org/pdf/1812.03115](http://arxiv.org/pdf/1812.03115)

