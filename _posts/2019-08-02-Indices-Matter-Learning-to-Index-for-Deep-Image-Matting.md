---
layout: post
title: "Indices Matter: Learning to Index for Deep Image Matting"
date: 2019-08-02 01:10:42
categories: arXiv_CV
tags: arXiv_CV CNN
author: Hao Lu, Yutong Dai, Chunhua Shen, Songcen Xu
mathjax: true
---

* content
{:toc}

##### Abstract
We show that existing upsampling operators can be unified with the notion of the index function. This notion is inspired by an observation in the decoding process of deep image matting where indices-guided unpooling can recover boundary details much better than other upsampling operators such as bilinear interpolation. By looking at the indices as a function of the feature map, we introduce the concept of learning to index, and present a novel index-guided encoder-decoder framework where indices are self-learned adaptively from data and are used to guide the pooling and upsampling operators, without the need of supervision. At the core of this framework is a flexible network module, termed IndexNet, which dynamically predicts indices given an input. Due to its flexibility, IndexNet can be used as a plug-in applying to any off-the-shelf convolutional networks that have coupled downsampling and upsampling stages. 
 We demonstrate the effectiveness of IndexNet on the task of natural image matting where the quality of learned indices can be visually observed from predicted alpha mattes. Results on the Composition-1k matting dataset show that our model built on MobileNetv2 exhibits at least $16.1\%$ improvement over the seminal VGG-16 based deep matting baseline, with less training data and lower model capacity. Code and models has been made available at: https://tinyurl.com/IndexNetV1

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.00672](http://arxiv.org/abs/1908.00672)

##### PDF
[http://arxiv.org/pdf/1908.00672](http://arxiv.org/pdf/1908.00672)

