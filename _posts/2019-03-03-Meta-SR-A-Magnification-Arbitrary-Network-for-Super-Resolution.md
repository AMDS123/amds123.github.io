---
layout: post
title: "Meta-SR: A Magnification-Arbitrary Network for Super-Resolution"
date: 2019-03-03 10:17:45
categories: arXiv_CV
tags: arXiv_CV Super_Resolution CNN
author: Xuecai Hu, Haoyuan Mu, Xiangyu Zhang, Zilei Wang, Jian Sun, Tieniu Tan
mathjax: true
---

* content
{:toc}

##### Abstract
Recent research on super-resolution has achieved great success due to the development of deep convolutional neural networks (DCNNs). However, super-resolution of arbitrary scale factor has been ignored for a long time. Most previous researchers regard super-resolution of different scale factors as independent tasks. They train a specific model for each scale factor which is inefficient in computing, and prior work only take the super-resolution of several integer scale factors into consideration. In this work, we propose a novel method called Meta-SR to firstly solve super-resolution of arbitrary scale factor (including non-integer scale factors) with a single model. In our Meta-SR, the Meta-Upscale Module is proposed to replace the traditional upscale module. For arbitrary scale factor, the Meta-Upscale Module dynamically predicts the weights of the upscale filters by taking the scale factor as input and use these weights to generate the HR image of arbitrary size. For any low-resolution image, our Meta-SR can continuously zoom in it with arbitrary scale factor by only using a single model. We evaluated the proposed method through extensive experiments on widely used benchmark datasets on single image super-resolution. The experimental results show the superiority of our Meta-Upscale.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.00875](http://arxiv.org/abs/1903.00875)

##### PDF
[http://arxiv.org/pdf/1903.00875](http://arxiv.org/pdf/1903.00875)

