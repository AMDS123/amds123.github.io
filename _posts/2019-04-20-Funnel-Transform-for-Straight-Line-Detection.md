---
layout: post
title: "Funnel Transform for Straight Line Detection"
date: 2019-04-20 07:30:11
categories: arXiv_CV
tags: arXiv_CV Detection
author: QianRu Wei, DaZheng Feng, WeiXing Zheng
mathjax: true
---

* content
{:toc}

##### Abstract
Most of the classical approaches to straight line detection only deal with a binary edge image and need to use 2D interpolation operation. This paper proposes a new transform method figuratively named as funnel transform which can efficiently and rapidly detect straight lines. The funnel transform consists of three 1D Fourier transforms and one nonlinear variable-metric transform (NVMT). It only needs to exploit 1D interpolation operation for achieving its NVMT, and can directly handle grayscale images by using its high-pass filter property, which significantly improves the performance of the closely-related approaches. Based on the slope-intercept line equation, the funnel transform can more uniformly turn the straight lines formed by ridge-typical and step-typical edges into the local maximum points (peaks). The parameters of each line can be uniquely extracted from its corresponding peak coordinates. Additionally, each peak can be theoretically specified by a 2D delta function, which makes the peaks and lines more easily identified and detected, respectively. Theoretical analysis and experimental results demonstrate that the funnel transform has advantages including smaller computational complexity, lower hardware cost, higher detection probability, greater location precision, better parallelization properties, stronger anti-occlusion and noise robustness.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.09409](http://arxiv.org/abs/1904.09409)

##### PDF
[http://arxiv.org/pdf/1904.09409](http://arxiv.org/pdf/1904.09409)

