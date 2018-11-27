---
layout: post
title: "On Periodic Functions as Regularizers for Quantization of Neural Networks"
date: 2018-11-24 17:24:28
categories: arXiv_CV
tags: arXiv_CV Regularization Deep_Learning
author: Maxim Naumov, Utku Diril, Jongsoo Park, Benjamin Ray, Jedrzej Jablonski, Andrew Tulloch
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning models have been successfully used in computer vision and many other fields. We propose an unorthodox algorithm for performing quantization of the model parameters. In contrast with popular quantization schemes based on thresholds, we use a novel technique based on periodic functions, such as continuous trigonometric sine or cosine as well as non-continuous hat functions. We apply these functions component-wise and add the sum over the model parameters as a regularizer to the model loss during training. The frequency and amplitude hyper-parameters of these functions can be adjusted during training. The regularization pushes the weights into discrete points that can be encoded as integers. We show that using this technique the resulting quantized models exhibit the same accuracy as the original ones on CIFAR-10 and ImageNet datasets.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1811.09862](https://arxiv.org/abs/1811.09862)

##### PDF
[https://arxiv.org/pdf/1811.09862](https://arxiv.org/pdf/1811.09862)

