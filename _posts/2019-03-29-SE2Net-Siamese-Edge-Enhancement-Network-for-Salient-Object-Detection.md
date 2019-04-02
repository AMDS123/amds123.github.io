---
layout: post
title: "SE2Net: Siamese Edge-Enhancement Network for Salient Object Detection"
date: 2019-03-29 18:50:10
categories: arXiv_CV
tags: arXiv_CV Salient Object_Detection CNN Inference Detection
author: Sanping Zhou, Jinjun Wang, Fei Wang, Dong Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolutional neural network significantly boosted the capability of salient object detection in handling large variations of scenes and object appearances. However, convolution operations seek to generate strong responses on individual pixels, while lack the ability to maintain the spatial structure of objects. Moreover, the down-sampling operations, such as pooling and striding, lose spatial details of the salient objects. In this paper, we propose a simple yet effective Siamese Edge-Enhancement Network (SE2Net) to preserve the edge structure for salient object detection. Specifically, a novel multi-stage siamese network is built to aggregate the low-level and high-level features, and parallelly estimate the salient maps of edges and regions. As a result, the predicted regions become more accurate by enhancing the responses at edges, and the predicted edges become more semantic by suppressing the false positives in background. After the refined salient maps of edges and regions are produced by the SE2Net, an edge-guided inference algorithm is designed to further improve the resulting salient masks along the predicted edges. Extensive experiments on several benchmark datasets have been conducted, which show that our method is superior than the state-of-the-art approaches.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.00048](http://arxiv.org/abs/1904.00048)

##### PDF
[http://arxiv.org/pdf/1904.00048](http://arxiv.org/pdf/1904.00048)

