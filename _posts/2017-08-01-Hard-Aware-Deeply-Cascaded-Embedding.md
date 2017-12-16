---
layout: post
title: "Hard-Aware Deeply Cascaded Embedding"
date: 2017-08-01 07:22:25
categories: arXiv_CV
tags: arXiv_CV Embedding
author: Yuhui Yuan, Kuiyuan Yang, Chao Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Riding on the waves of deep neural networks, deep metric learning has also achieved promising results in various tasks using triplet network or Siamese network. Though the basic goal of making images from the same category closer than the ones from different categories is intuitive, it is hard to directly optimize due to the quadratic or cubic sample size. To solve the problem, hard example mining which only focuses on a subset of samples that are considered hard is widely used. However, hard is defined relative to a model, where complex models treat most samples as easy ones and vice versa for simple models, and both are not good for training. Samples are also with different hard levels, it is hard to define a model with the just right complexity and choose hard examples adequately. This motivates us to ensemble a set of models with different complexities in cascaded manner and mine hard examples adaptively, a sample is judged by a series of models with increasing complexities and only updates models that consider the sample as a hard case. We evaluate our method on CARS196, CUB-200-2011, Stanford Online Products, VehicleID and DeepFashion datasets. Our method outperforms state-of-the-art methods by a large margin.

##### Abstract (translated by Google)
在深度神经网络的浪潮中，深度量学习在使用三元网络或连体网络的各种任务中也取得了可喜的成果。虽然从同一类别的图像比不同类别的图像更接近的基本目标是直观的，但由于二次或三次样本大小很难直接优化。为了解决这个问题，仅仅关注被认为是难以处理的样本子集的硬性示例挖掘被广泛使用。然而，难度是相对于模型来定义的，其中复杂模型将大多数样本视为简单模型，反之亦然，对于简单模型，两者都不利于训练。样本也有不同的难度，很难用恰到好处的复杂度来定义一个模型，并充分选择实例。这促使我们以级联的方式集合一组具有不同复杂性的模型，并自适应地挖掘硬实例，一个样本通过一系列复杂性增加的模型来判断，并且只更新认为样本是硬实例的模型。我们在CARS196，CUB-200-2011，Stanford Online Products，VehicleID和DeepFashion数据集上评估我们的方法。我们的方法大大超过了最先进的方法。

##### URL
[https://arxiv.org/abs/1611.05720](https://arxiv.org/abs/1611.05720)

##### PDF
[https://arxiv.org/pdf/1611.05720](https://arxiv.org/pdf/1611.05720)

