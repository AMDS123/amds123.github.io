---
layout: post
title: "ECO: Efficient Convolution Operators for Tracking"
date: 2017-04-10 18:13:05
categories: arXiv_CV
tags: arXiv_CV Tracking Relation
author: Martin Danelljan, Goutam Bhat, Fahad Shahbaz Khan, Michael Felsberg
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, Discriminative Correlation Filter (DCF) based methods have significantly advanced the state-of-the-art in tracking. However, in the pursuit of ever increasing tracking performance, their characteristic speed and real-time capability have gradually faded. Further, the increasingly complex models, with massive number of trainable parameters, have introduced the risk of severe over-fitting. In this work, we tackle the key causes behind the problems of computational complexity and over-fitting, with the aim of simultaneously improving both speed and performance. We revisit the core DCF formulation and introduce: (i) a factorized convolution operator, which drastically reduces the number of parameters in the model; (ii) a compact generative model of the training sample distribution, that significantly reduces memory and time complexity, while providing better diversity of samples; (iii) a conservative model update strategy with improved robustness and reduced complexity. We perform comprehensive experiments on four benchmarks: VOT2016, UAV123, OTB-2015, and TempleColor. When using expensive deep features, our tracker provides a 20-fold speedup and achieves a 13.0% relative gain in Expected Average Overlap compared to the top ranked method in the VOT2016 challenge. Moreover, our fast variant, using hand-crafted features, operates at 60 Hz on a single CPU, while obtaining 65.0% AUC on OTB-2015.

##### Abstract (translated by Google)
近年来，基于判别相关滤波器（DCF）的方法已经显着地推进了最新的跟踪。但是在追求性能不断提高的同时，其特征速度和实时性也逐渐淡化。此外，越来越复杂的模型，大量的可训练参数引入了严重过度的风险。在这项工作中，我们解决了计算复杂性和过度拟合问题背后的关键原因，目的是同时提高速度和性能。我们重新审视核心DCF公式，并引入：（i）分解卷积算子，大大减少了模型中的参数数目; （ii）训练样本分布的紧凑生成模型，其显着降低记忆和时间复杂度，同时提供更好的样本多样性; （iii）保守的模型更新策略，具有改进的鲁棒性和降低的复杂性。我们在四个基准上进行了全面的实验：VOT2016，UAV123，OTB-2015和TempleColor。当使用昂贵的深度特征时，与VOT2016挑战中排名靠前的方法相比，我们的跟踪器提供了20倍的加速比，并且在预期平均重叠方面获得了13.0％的相对增益。此外，我们采用手工功能的快速变型在单个CPU上以60 Hz工作，同时在OTB-2015上获得了65.0％的AUC。

##### URL
[https://arxiv.org/abs/1611.09224](https://arxiv.org/abs/1611.09224)

##### PDF
[https://arxiv.org/pdf/1611.09224](https://arxiv.org/pdf/1611.09224)

