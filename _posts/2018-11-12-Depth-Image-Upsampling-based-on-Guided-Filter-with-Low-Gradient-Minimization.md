---
layout: post
title: "Depth Image Upsampling based on Guided Filter with Low Gradient Minimization"
date: 2018-11-12 09:36:12
categories: arXiv_CV
tags: arXiv_CV Regularization Sparse Quantitative
author: Hang Yang, Zhongbo Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a novel upsampling framework to enhance the spatial resolution of the depth image. In our framework, the upscaling of a low-resolution depth image is guided by a corresponding intensity images, we formulate it as a cost aggregation problem with the guided filter. However, the guided filter does not make full use of the properties of the depth image. Since depth images have quite sparse gradients, it inspires us to regularize the gradients for improving depth upscaling results. Statistics show a special property of depth images, that is, there is a non-ignorable part of pixels whose horizontal or vertical derivatives are equal to $\pm 1$. Considering this special property, we propose a low gradient regularization method which reduces the penalty for horizontal or vertical derivative $\pm1$. The proposed low gradient regularization is integrated with the guided filter into the depth image upsampling method. Experimental results demonstrate the effectiveness of our proposed approach both qualitatively and quantitatively compared with the state-of-the-art methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.04620](http://arxiv.org/abs/1811.04620)

##### PDF
[http://arxiv.org/pdf/1811.04620](http://arxiv.org/pdf/1811.04620)

