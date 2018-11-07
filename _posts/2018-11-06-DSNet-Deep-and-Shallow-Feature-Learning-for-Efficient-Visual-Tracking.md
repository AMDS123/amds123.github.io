---
layout: post
title: "DSNet: Deep and Shallow Feature Learning for Efficient Visual Tracking"
date: 2018-11-06 07:55:42
categories: arXiv_CV
tags: arXiv_CV GAN Tracking CNN Image_Classification Classification Relation
author: Qiangqiang Wu, Yan Yan, Yanjie Liang, Yi Liu, Hanzi Wang
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, Discriminative Correlation Filter (DCF) based tracking methods have achieved great success in visual tracking. However, the multi-resolution convolutional feature maps trained from other tasks like image classification, cannot be naturally used in the conventional DCF formulation. Furthermore, these high-dimensional feature maps significantly increase the tracking complexity and thus limit the tracking speed. In this paper, we present a deep and shallow feature learning network, namely DSNet, to learn the multi-level same-resolution compressed (MSC) features for efficient online tracking, in an end-to-end offline manner. Specifically, the proposed DSNet compresses multi-level convolutional features to uniform spatial resolution features. The learned MSC features effectively encode both appearance and semantic information of objects in the same-resolution feature maps, thus enabling an elegant combination of the MSC features with any DCF-based methods. Additionally, a channel reliability measurement (CRM) method is presented to further refine the learned MSC features. We demonstrate the effectiveness of the MSC features learned from the proposed DSNet on two DCF tracking frameworks: the basic DCF framework and the continuous convolution operator framework. Extensive experiments show that the learned MSC features have the appealing advantage of allowing the equipped DCF-based tracking methods to perform favorably against the state-of-the-art methods while running at high frame rates.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1811.02208](https://arxiv.org/abs/1811.02208)

##### PDF
[https://arxiv.org/pdf/1811.02208](https://arxiv.org/pdf/1811.02208)

