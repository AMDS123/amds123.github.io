---
layout: post
title: "SAN: Learning Relationship between Convolutional Features for Multi-Scale Object Detection"
date: 2018-08-15 05:35:44
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection Relation
author: Yonghyun Kim, Bong-Nam Kang, Daijin Kim
mathjax: true
---

* content
{:toc}

##### Abstract
Most of the recent successful methods in accurate object detection build on the convolutional neural networks (CNN). However, due to the lack of scale normalization in CNN-based detection methods, the activated channels in the feature space can be completely different according to a scale and this difference makes it hard for the classifier to learn samples. We propose a Scale Aware Network (SAN) that maps the convolutional features from the different scales onto a scale-invariant subspace to make CNN-based detection methods more robust to the scale variation, and also construct a unique learning method which considers purely the relationship between channels without the spatial information for the efficient learning of SAN. To show the validity of our method, we visualize how convolutional features change according to the scale through a channel activation matrix and experimentally show that SAN reduces the feature differences in the scale space. We evaluate our method on VOC PASCAL and MS COCO dataset. We demonstrate SAN by conducting several experiments on structures and parameters. The proposed SAN can be generally applied to many CNN-based detection methods to enhance the detection accuracy with a slight increase in the computing time.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1808.04974](https://arxiv.org/abs/1808.04974)

##### PDF
[https://arxiv.org/pdf/1808.04974](https://arxiv.org/pdf/1808.04974)

