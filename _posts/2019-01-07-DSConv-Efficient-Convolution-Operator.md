---
layout: post
title: "DSConv: Efficient Convolution Operator"
date: 2019-01-07 17:18:16
categories: arXiv_CV
tags: arXiv_CV CNN
author: Marcelo Gennari, Roger Fawcett, Victor Adrian Prisacariu
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a variation of the convolutional layer called DSConv (Distribution Shifting Convolution) that can be readily substituted into standard neural network architectures and achieve both lower memory usage and higher computational speed. DSConv breaks down the traditional convolution kernel into two components: Variable Quantized Kernel (VQK), and Distribution Shifts. Lower memory usage and higher speeds are achieved by storing only integer values in the VQK, whilst preserving the same output as the original convolution by applying both kernel and channel based distribution shifts. We test DSConv in ImageNet on ResNet50 and 34, as well as AlexNet and MobileNet. We achieve a reduction in memory usage of up to 14x in the convolutional kernels and speed up operations of up to 10x by substituting floating point operations to integer operations. Furthermore, unlike other quantization approaches, our work allows for a degree of retraining to new tasks and datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.01928](http://arxiv.org/abs/1901.01928)

##### PDF
[http://arxiv.org/pdf/1901.01928](http://arxiv.org/pdf/1901.01928)

