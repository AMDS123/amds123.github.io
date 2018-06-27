---
layout: post
title: "Multi-Mapping Image-to-Image Translation with Central Biasing Normalization"
date: 2018-06-26 15:07:42
categories: arXiv_CV
tags: arXiv_CV Quantitative
author: Xiaoming Yu, Zhenqiang Ying, Ge Li, Wen Gao
mathjax: true
---

* content
{:toc}

##### Abstract
Recent image-to-image translation tasks attempt to extend the model from one-to-one mapping to multiple mappings by injecting latent code. Based on the mathematical formulation of networks with existing way of latent code injection, we show the role of latent code is to control the mean of the feature maps after convolution. Then we find common normalization strategies might reduce the diversity of different mappings or the consistency of one specific mapping, which is not suitable for the multi-mapping tasks. We provide the mathematical derivation that the effects of latent code are eliminated after instance normalization and the distributions of the same mapping become inconsistent after batch normalization. To address these problems, we present consistency within diversity design criteria for multi-mapping networks and propose central biasing normalization by applying a slight yet significant change to existing normalization strategies. Instead of spatial replicating and concatenating into the input layers, we inject the latent code into the normalization layers where the offset of feature maps is eliminated to ensure the output consistency for one specific mapping and the bias calculated by latent code is appended to achieve the output diversity for different mappings. In this way, not only is the proposed design criteria met, but the modified generator network has much smaller number of parameters. We apply this technique to multi-modal and multi-domain translation tasks. Both quantitative and qualitative evaluations show that our method outperforms current state-of-the-art methods. Code and pretrained models are available at https://github.com/Xiaoming-Yu/cbn.

##### Abstract (translated by Google)
最近的图像到图像转换任务试图通过注入潜在代码将模型从一对一映射扩展到多个映射。基于现有潜在码注入方式的网络数学公式，我们表明潜在码的作用是控制卷积后特征映射的均值。然后我们发现常用的规范化策略可能会减少不同映射的多样性或者一个特定映射的一致性，这不适用于多映射任务。我们提供了数学推导，即在实例标准化之后消除潜在代码的影响并且在批量标准化之后相同映射的分布变得不一致。为了解决这些问题，我们针对多映射网络的多样性设计标准提出了一致性，并通过对现有的标准化策略应用轻微而显着的变化来提出中央偏置标准化。我们将潜在代码注入标准化图层，而不是空间复制并连接到输入图层，而是将特征映射的偏移量消除，以确保一个特定映射的输出一致性，并附加潜在代码计算的偏差以实现输出不同映射的多样性。通过这种方式，不仅满足了所提出的设计标准，而且修改后的发电机网络的参数数量也少得多。我们将此技术应用于多模态和多域翻译任务。定量和定性评估都表明，我们的方法优于当前最先进的方法。代码和预训练模型可在https://github.com/Xiaoming-Yu/cbn获得。

##### URL
[http://arxiv.org/abs/1806.10050](http://arxiv.org/abs/1806.10050)

##### PDF
[http://arxiv.org/pdf/1806.10050](http://arxiv.org/pdf/1806.10050)

