---
layout: post
title: "Index Network"
date: 2019-08-11 10:52:47
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Prediction
author: Hao Lu, Yutong Dai, Chunhua Shen, Songcen Xu
mathjax: true
---

* content
{:toc}

##### Abstract
We show that existing upsampling operators can be unified using the notion of the index function. This notion is inspired by an observation in the decoding process of deep image matting where indices-guided unpooling can often recover boundary details considerably better than other upsampling operators such as bilinear interpolation. By viewing the indices as a function of the feature map, we introduce the concept of "learning to index", and present a novel index-guided encoder-decoder framework where indices are self-learned adaptively from data and are used to guide the downsampling and upsampling stages, without extra training supervision. At the core of this framework is a new learnable module, termed Index Network (IndexNet), which dynamically generates indices conditioned on the feature map itself. IndexNet can be used as a plug-in applying to almost all off-the-shelf convolutional networks that have coupled downsampling and upsampling stages, giving the networks the ability to dynamically capture variations of local patterns. In particular, we instantiate and investigate five families of IndexNet and demonstrate their effectiveness on four dense prediction tasks, including image denoising, image matting, semantic segmentation, and monocular depth estimation. Code and models have been made available at: https://tinyurl.com/IndexNetV1

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.09895](http://arxiv.org/abs/1908.09895)

##### PDF
[http://arxiv.org/pdf/1908.09895](http://arxiv.org/pdf/1908.09895)

