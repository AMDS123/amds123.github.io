---
layout: post
title: "Deep Concept-wise Temporal Convolutional Networks for Action Localization"
date: 2019-08-26 02:56:07
categories: arXiv_CV
tags: arXiv_CV CNN Classification
author: Xin Li, Tianwei Lin, Xiao Liu, Chuang Gan, Wangmeng Zuo, Chao Li, Xiang Long, Dongliang He, Fu Li, Shilei Wen
mathjax: true
---

* content
{:toc}

##### Abstract
Existing action localization approaches adopt shallow temporal convolutional networks (\ie, TCN) on 1D feature map extracted from video frames. In this paper, we empirically find that stacking more conventional temporal convolution layers actually deteriorates action classification performance, possibly ascribing to that all channels of 1D feature map, which generally are highly abstract and can be regarded as latent concepts, are excessively recombined in temporal convolution. To address this issue, we introduce a novel concept-wise temporal convolution (CTC) layer as an alternative to conventional temporal convolution layer for training deeper action localization networks. Instead of recombining latent concepts, CTC layer deploys a number of temporal filters to each concept separately with shared filter parameters across concepts. Thus can capture common temporal patterns of different concepts and significantly enrich representation ability. Via stacking CTC layers, we proposed a deep concept-wise temporal convolutional network (C-TCN), which boosts the state-of-the-art action localization performance on THUMOS'14 from 42.8 to 52.1 in terms of mAP(\%), achieving a relative improvement of 21.7\%. Favorable result is also obtained on ActivityNet.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.09442](http://arxiv.org/abs/1908.09442)

##### PDF
[http://arxiv.org/pdf/1908.09442](http://arxiv.org/pdf/1908.09442)

