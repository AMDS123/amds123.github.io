---
layout: post
title: "Making Convolutional Networks Shift-Invariant Again"
date: 2019-04-25 17:56:21
categories: arXiv_CV
tags: arXiv_CV Regularization CNN Image_Classification Classification
author: Richard Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Modern convolutional networks are not shift-invariant, as small input shifts or translations can cause drastic changes in the output. Commonly used downsampling methods, such as max-pooling, strided-convolution, and average-pooling, ignore the sampling theorem. The well-known signal processing fix is anti-aliasing by low-pass filtering before downsampling. However, simply inserting this module into deep networks leads to performance degradation; as a result, it is seldomly used today. We show that when integrated correctly, it is compatible with existing architectural components, such as max-pooling. The technique is general and can be incorporated across layer types and applications, such as image classification and conditional image generation. In addition to increased shift-invariance, we also observe, surprisingly, that anti-aliasing boosts accuracy in ImageNet classification, across several commonly-used architectures. This indicates that anti-aliasing serves as effective regularization. Our results demonstrate that this classical signal processing technique has been undeservingly overlooked in modern deep networks. Code and anti-aliased versions of popular networks will be made available at \url{https://richzhang.github.io/antialiased-cnns/} .

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.11486](http://arxiv.org/abs/1904.11486)

##### PDF
[http://arxiv.org/pdf/1904.11486](http://arxiv.org/pdf/1904.11486)

