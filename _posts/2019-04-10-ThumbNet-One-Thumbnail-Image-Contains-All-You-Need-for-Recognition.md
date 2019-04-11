---
layout: post
title: "ThumbNet: One Thumbnail Image Contains All You Need for Recognition"
date: 2019-04-10 07:44:09
categories: arXiv_CV
tags: arXiv_CV CNN Inference Classification Recognition
author: Chen Zhao, Bernard Ghanem
mathjax: true
---

* content
{:toc}

##### Abstract
Although deep convolutional neural networks (CNNs) have achieved great success in the computer vision community, its real-world application is still impeded by its voracious demand of computational resources. Current works mostly seek to compress the network by reducing its parameters or parameter-incurred computation, neglecting the influence of the input image on the system complexity. Based on the fact that input images of a CNN contain much redundant spatial content, we propose in this paper an efficient and unified framework, dubbed as ThumbNet, to simultaneously accelerate and compress CNN models by enabling them to infer on one thumbnail image. We provide three effective strategies to train ThumbNet. In doing so, ThumbNet learns an inference network that performs equally well on small images as the original-input network on large images. With ThumbNet, not only do we obtain the thumbnail-input inference network that can drastically reduce computation and memory requirements, but also we obtain an image downscaler that can generate thumbnail images for generic classification tasks. Extensive experiments show the effectiveness of ThumbNet, and demonstrate that the thumbnail-input inference network learned by ThumbNet can adequately retain the accuracy of the original-input network even when the input images are downscaled 16 times.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.05034](http://arxiv.org/abs/1904.05034)

##### PDF
[http://arxiv.org/pdf/1904.05034](http://arxiv.org/pdf/1904.05034)

