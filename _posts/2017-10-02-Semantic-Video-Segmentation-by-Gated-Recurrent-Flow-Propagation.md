---
layout: post
title: "Semantic Video Segmentation by Gated Recurrent Flow Propagation"
date: 2017-10-02 07:52:42
categories: arXiv_CV
tags: arXiv_CV Segmentation Weakly_Supervised CNN Semantic_Segmentation Recognition
author: David Nilsson, Cristian Sminchisescu
mathjax: true
---

* content
{:toc}

##### Abstract
Semantic video segmentation is challenging due to the sheer amount of data that needs to be processed and labeled in order to construct accurate models. In this paper we present a deep, end-to-end trainable methodology to video segmentation that is capable of leveraging information present in unlabeled data in order to improve semantic estimates. Our model combines a convolutional architecture and a spatio-temporal transformer recurrent layer that are able to temporally propagate labeling information by means of optical flow, adaptively gated based on its locally estimated uncertainty. The flow, the recognition and the gated temporal propagation modules can be trained jointly, end-to-end. The temporal, gated recurrent flow propagation component of our model can be plugged into any static semantic segmentation architecture and turn it into a weakly supervised video processing one. Our extensive experiments in the challenging CityScapes and Camvid datasets, and based on multiple deep architectures, indicate that the resulting model can leverage unlabeled temporal frames, next to a labeled one, in order to improve both the video segmentation accuracy and the consistency of its temporal labeling, at no additional annotation cost and with little extra computation.

##### Abstract (translated by Google)
语义视频分割是具有挑战性的，因为需要处理和标记以构建精确模型的数据量非常大。在本文中，我们提出了一种深入的，端到端的可训练的视频分割方法，能够利用未标记数据中的信息来提高语义估计。我们的模型结合了卷积结构和时空变换器递归层，能够通过光流在时间上传播标记信息，基于其局部估计的不确定性自适应地选通。流，识别和门控时间传播模块可以共同地，端对端地训练。我们模型的时间门控循环流传播分量可以插入任何静态语义分割体系结构，并将其转化为弱监督视频处理。我们在具有挑战性的CityScapes和Camvid数据集中进行了广泛的实验，并且基于多种深度架构，表明所得到的模型可以利用未标记的时间帧，紧跟已标记的时间帧，以提高视频分割的准确性和时间一致性贴上标签，不需要额外的注释成本，只需少量额外的计算。

##### URL
[https://arxiv.org/abs/1612.08871](https://arxiv.org/abs/1612.08871)

##### PDF
[https://arxiv.org/pdf/1612.08871](https://arxiv.org/pdf/1612.08871)

