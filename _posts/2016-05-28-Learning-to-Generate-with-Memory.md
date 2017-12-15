---
layout: post
title: "Learning to Generate with Memory"
date: 2016-05-28 03:41:27
categories: arXiv_CV
tags: arXiv_CV Attention Represenation_Learning Prediction Recognition
author: Chongxuan Li, Jun Zhu, Bo Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Memory units have been widely used to enrich the capabilities of deep networks on capturing long-term dependencies in reasoning and prediction tasks, but little investigation exists on deep generative models (DGMs) which are good at inferring high-level invariant representations from unlabeled data. This paper presents a deep generative model with a possibly large external memory and an attention mechanism to capture the local detail information that is often lost in the bottom-up abstraction process in representation learning. By adopting a smooth attention model, the whole network is trained end-to-end by optimizing a variational bound of data likelihood via auto-encoding variational Bayesian methods, where an asymmetric recognition network is learnt jointly to infer high-level invariant representations. The asymmetric architecture can reduce the competition between bottom-up invariant feature extraction and top-down generation of instance details. Our experiments on several datasets demonstrate that memory can significantly boost the performance of DGMs and even achieve state-of-the-art results on various tasks, including density estimation, image generation, and missing value imputation.

##### Abstract (translated by Google)
内存单元已被广泛用于丰富深层网络在推理和预测任务中捕获长期依赖性的能力，但对深层生成模型（DGM）的研究却很少，它能很好地从未标记的数据中推断出高层不变的表示。本文提出了一个深度生成模型，它具有可能的大的外部记忆和一个注意机制来捕捉在表征学习中自下而上的抽象过程中常常丢失的局部细节信息。通过采用平滑的关注模型，通过自动编码变分贝叶斯方法优化数据似然的变分边界，对整个网络进行端到端的训练，其中不对称识别网络共同学习推断高层不变表示。非对称架构可以减少自底向上不变特征提取与实例细节自顶向下生成之间的竞争。我们对多个数据集的实验表明，内存可显着提升DGM的性能，甚至可以在各种任务（包括密度估计，图像生成和缺失值插补）上实现最新的结果。

##### URL
[https://arxiv.org/abs/1602.07416](https://arxiv.org/abs/1602.07416)

##### PDF
[https://arxiv.org/pdf/1602.07416](https://arxiv.org/pdf/1602.07416)

