---
layout: post
title: "Multi-Bias Non-linear Activation in Deep Neural Networks"
date: 2016-04-03 19:31:22
categories: arXiv_CV
tags: arXiv_CV Classification
author: Hongyang Li, Wanli Ouyang, Xiaogang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
As a widely used non-linear activation, Rectified Linear Unit (ReLU) separates noise and signal in a feature map by learning a threshold or bias. However, we argue that the classification of noise and signal not only depends on the magnitude of responses, but also the context of how the feature responses would be used to detect more abstract patterns in higher layers. In order to output multiple response maps with magnitude in different ranges for a particular visual pattern, existing networks employing ReLU and its variants have to learn a large number of redundant filters. In this paper, we propose a multi-bias non-linear activation (MBA) layer to explore the information hidden in the magnitudes of responses. It is placed after the convolution layer to decouple the responses to a convolution kernel into multiple maps by multi-thresholding magnitudes, thus generating more patterns in the feature space at a low computational cost. It provides great flexibility of selecting responses to different visual patterns in different magnitude ranges to form rich representations in higher layers. Such a simple and yet effective scheme achieves the state-of-the-art performance on several benchmarks.

##### Abstract (translated by Google)
整流线性单元（ReLU）作为一种广泛应用的非线性激励，通过学习阈值或偏差来分离特征图中的噪声和信号。然而，我们认为噪声和信号的分类不仅取决于响应的大小，而且还取决于如何使用特征响应来检测更高层中更抽象的模式。为了输出具有不同范围幅度的多个响应图以用于特定的视觉模式，使用ReLU及其变体的现有网络必须学习大量的冗余滤波器。在本文中，我们提出了一个多偏置非线性激活（MBA）层来探索隐藏在响应量级中的信息。它放置在卷积层之后，通过多阈值幅度将对卷积核的响应解耦成多个映射，从而在低的计算成本下在特征空间中生成更多的模式。它提供了很大的灵活性，选择不同的视觉模式在不同幅度范围内的反应，形成更高层次的丰富的表现形式。这样一个简单而有效的方案在几个基准上达到了最先进的性能。

##### URL
[https://arxiv.org/abs/1604.00676](https://arxiv.org/abs/1604.00676)

##### PDF
[https://arxiv.org/pdf/1604.00676](https://arxiv.org/pdf/1604.00676)

