---
layout: post
title: "Component-Based Distributed Framework for Coherent and Real-Time Video Dehazing"
date: 2016-09-09 16:14:01
categories: arXiv_CV
tags: arXiv_CV
author: Meihua Wang, Jiaming Mai, Yun Liang, Tom Z. J. Fu, Zhenjie Zhang, Ruichu Cai
mathjax: true
---

* content
{:toc}

##### Abstract
Traditional dehazing techniques, as a well studied topic in image processing, are now widely used to eliminate the haze effects from individual images. However, even the state-of-the-art dehazing algorithms may not provide sufficient support to video analytics, as a crucial pre-processing step for video-based decision making systems (e.g., robot navigation), due to the limitations of these algorithms on poor result coherence and low processing efficiency. This paper presents a new framework, particularly designed for video dehazing, to output coherent results in real time, with two novel techniques. Firstly, we decompose the dehazing algorithms into three generic components, namely transmission map estimator, atmospheric light estimator and haze-free image generator. They can be simultaneously processed by multiple threads in the distributed system, such that the processing efficiency is optimized by automatic CPU resource allocation based on the workloads. Secondly, a cross-frame normalization scheme is proposed to enhance the coherence among consecutive frames, by sharing the parameters of atmospheric light from consecutive frames in the distributed computation platform. The combination of these techniques enables our framework to generate highly consistent and accurate dehazing results in real-time, by using only 3 PCs connected by Ethernet.

##### Abstract (translated by Google)
传统的除雾技术作为图像处理领域的一个研究热点，目前被广泛用于消除个体图像的雾影响。然而，由于这些算法的限制，即使最先进的除雾算法也不能为视频分析提供足够的支持，作为基于视频的决策系统（例如，机器人导航）的关键预处理步骤结果连贯性差，处理效率低。本文提出了一个新的框架，特别是视频除雾设计，用两种新颖的技术实时输出一致的结果。首先，将去雾算法分解为三个通用分量，即透射图估计器，大气光估计器和无雾图像生成器。它们可以在分布式系统中通过多个线程同时进行处理，从而通过基于工作负载的自动CPU资源分配来优化处理效率。其次，通过分布式计算平台中连续帧的大气光参数共享，提出了一种跨帧归一化方案，以提高连续帧间的一致性。这些技术的结合使我们的框架能够实时生成高度一致和准确的除雾结果，仅使用3台通过以太网连接的PC。

##### URL
[https://arxiv.org/abs/1609.02035](https://arxiv.org/abs/1609.02035)

##### PDF
[https://arxiv.org/pdf/1609.02035](https://arxiv.org/pdf/1609.02035)

