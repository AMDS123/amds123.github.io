---
layout: post
title: "PatchBatch: a Batch Augmented Loss for Optical Flow"
date: 2016-04-10 14:17:18
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: David Gadot, Lior Wolf
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new pipeline for optical flow computation, based on Deep Learning techniques. We suggest using a Siamese CNN to independently, and in parallel, compute the descriptors of both images. The learned descriptors are then compared efficiently using the L2 norm and do not require network processing of patch pairs. The success of the method is based on an innovative loss function that computes higher moments of the loss distributions for each training batch. Combined with an Approximate Nearest Neighbor patch matching method and a flow interpolation technique, state of the art performance is obtained on the most challenging and competitive optical flow benchmarks.

##### Abstract (translated by Google)
我们提出了一个基于深度学习技术的光流计算新途径。我们建议独立使用连体CNN，并行计算两个图像的描述符。然后使用L2规范有效地比较所学习的描述符，并且不需要网络处理补丁对。该方法的成功基于一个创新的损失函数，计算每个培训批次的损失分布的较高时刻。结合近似最近邻片匹配方法和流量插值技术，在最具挑战性和竞争力的光流基准上获得了最先进的性能。

##### URL
[https://arxiv.org/abs/1512.01815](https://arxiv.org/abs/1512.01815)

##### PDF
[https://arxiv.org/pdf/1512.01815](https://arxiv.org/pdf/1512.01815)

