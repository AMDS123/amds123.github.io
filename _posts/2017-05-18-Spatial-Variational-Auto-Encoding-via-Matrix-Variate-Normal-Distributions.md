---
layout: post
title: "Spatial Variational Auto-Encoding via Matrix-Variate Normal Distributions"
date: 2017-05-18 22:32:57
categories: arXiv_CV
tags: arXiv_CV
author: Zhengyang Wang, Hao Yuan, Shuiwang Ji
mathjax: true
---

* content
{:toc}

##### Abstract
The key idea of variational auto-encoders (VAEs) resembles that of traditional auto-encoder models in which spatial information is supposed to be explicitly encoded in the latent space. However, the latent variables in VAEs are vectors, which are commonly interpreted as multiple feature maps of size 1x1. Such representations can only convey spatial information implicitly when coupled with powerful decoders. In this work, we propose spatial VAEs that use latent variables as feature maps of larger size to explicitly capture spatial information. This is achieved by allowing the latent variables to be sampled from matrix-variate normal (MVN) distributions whose parameters are computed from the encoder network. To increase dependencies among locations on latent feature maps and reduce the number of parameters, we further propose spatial VAEs via low-rank MVN distributions. Experimental results show that the proposed spatial VAEs outperform original VAEs in capturing rich structural and spatial information.

##### Abstract (translated by Google)
变分自动编码器（VAEs）的关键思想类似于传统的自动编码器模型，其中空间信息应该被显式编码在潜在空间中。然而，VAE中的潜在变量是向量，通常被解释为多个大小为1x1的特征映射。与强大的解码器结合时，这种表示只能隐含地传达空间信息。在这项工作中，我们提出空间VAE使用潜在变量作为更大尺寸的特征地图来明确地捕捉空间信息。这是通过允许从其编码器网络计算参数的矩阵变量正态（MVN）分布对潜变量进行采样来实现的。为了提高潜在特征地图上各个位置之间的依赖关系，减少参数数量，我们进一步提出了通过低秩MVN分布的空间VAE。实验结果表明，提出的空间VAEs在捕获丰富的结构和空间信息方面优于原始VAE。

##### URL
[https://arxiv.org/abs/1705.06821](https://arxiv.org/abs/1705.06821)

##### PDF
[https://arxiv.org/pdf/1705.06821](https://arxiv.org/pdf/1705.06821)

