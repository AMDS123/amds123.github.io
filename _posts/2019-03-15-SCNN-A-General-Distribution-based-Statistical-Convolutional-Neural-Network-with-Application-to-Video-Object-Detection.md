---
layout: post
title: "SCNN: A General Distribution based Statistical Convolutional Neural Network with Application to Video Object Detection"
date: 2019-03-15 16:00:23
categories: arXiv_CV
tags: arXiv_CV Object_Detection Tracking CNN Inference Detection Relation Recognition
author: Tianchen Wang, Jinjun Xiong, Xiaowei Xu, Yiyu Shi
mathjax: true
---

* content
{:toc}

##### Abstract
Various convolutional neural networks (CNNs) were developed recently that achieved accuracy comparable with that of human beings in computer vision tasks such as image recognition, object detection and tracking, etc. Most of these networks, however, process one single frame of image at a time, and may not fully utilize the temporal and contextual correlation typically present in multiple channels of the same image or adjacent frames from a video, thus limiting the achievable throughput. This limitation stems from the fact that existing CNNs operate on deterministic numbers. In this paper, we propose a novel statistical convolutional neural network (SCNN), which extends existing CNN architectures but operates directly on correlated distributions rather than deterministic numbers. By introducing a parameterized canonical model to model correlated data and defining corresponding operations as required for CNN training and inference, we show that SCNN can process multiple frames of correlated images effectively, hence achieving significant speedup over existing CNN models. We use a CNN based video object detection as an example to illustrate the usefulness of the proposed SCNN as a general network model. Experimental results show that even a non-optimized implementation of SCNN can still achieve 178% speedup over existing CNNs with slight accuracy degradation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.07663](http://arxiv.org/abs/1903.07663)

##### PDF
[http://arxiv.org/pdf/1903.07663](http://arxiv.org/pdf/1903.07663)

