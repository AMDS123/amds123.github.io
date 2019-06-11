---
layout: post
title: "Image-to-Image Translation via Group-wise Deep Whitening-and-Coloring Transformation"
date: 2019-06-09 08:58:05
categories: arXiv_CV
tags: arXiv_CV Regularization Style_Transfer Inference Quantitative
author: Wonwoong Cho, Sungha Choi, David Keetae Park, Inkyu Shin, Jaegul Choo
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, unsupervised exemplar-based image-to-image translation, conditioned on a given exemplar without the paired data, has accomplished substantial advancements. In order to transfer the information from an exemplar to an input image, existing methods often use a normalization technique, e.g., adaptive instance normalization, that controls the channel-wise statistics of an input activation map at a particular layer, such as the mean and the variance. Meanwhile, style transfer approaches similar task to image translation by nature, demonstrated superior performance by using the higher-order statistics such as covariance among channels in representing a style. In detail, it works via whitening (given a zero-mean input feature, transforming its covariance matrix into the identity). followed by coloring (changing the covariance matrix of the whitened feature to those of the style feature). However, applying this approach in image translation is computationally intensive and error-prone due to the expensive time complexity and its non-trivial backpropagation. In response, this paper proposes an end-to-end approach tailored for image translation that efficiently approximates this transformation with our novel regularization methods. We further extend our approach to a group-wise form for memory and time efficiency as well as image quality. Extensive qualitative and quantitative experiments demonstrate that our proposed method is fast, both in training and inference, and highly effective in reflecting the style of an exemplar. Finally, our code is available at https://github.com/WonwoongCho/GDWCT.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.09912](http://arxiv.org/abs/1812.09912)

##### PDF
[http://arxiv.org/pdf/1812.09912](http://arxiv.org/pdf/1812.09912)

