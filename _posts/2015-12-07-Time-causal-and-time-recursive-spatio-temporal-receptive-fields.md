---
layout: post
title: "Time-causal and time-recursive spatio-temporal receptive fields"
date: 2015-12-07 15:50:45
categories: arXiv_CV
tags: arXiv_CV Detection
author: Tony Lindeberg
mathjax: true
---

* content
{:toc}

##### Abstract
We present an improved model and theory for time-causal and time-recursive spatio-temporal receptive fields, based on a combination of Gaussian receptive fields over the spatial domain and first-order integrators or equivalently truncated exponential filters coupled in cascade over the temporal domain. Compared to previous spatio-temporal scale-space formulations in terms of non-enhancement of local extrema or scale invariance, these receptive fields are based on different scale-space axiomatics over time by ensuring non-creation of new local extrema or zero-crossings with increasing temporal scale. Specifically, extensions are presented about (i) parameterizing the intermediate temporal scale levels, (ii) analysing the resulting temporal dynamics, (iii) transferring the theory to a discrete implementation, (iv) computing scale-normalized spatio-temporal derivative expressions for spatio-temporal feature detection and (v) computational modelling of receptive fields in the lateral geniculate nucleus (LGN) and the primary visual cortex (V1) in biological vision. We show that by distributing the intermediate temporal scale levels according to a logarithmic distribution, we obtain much faster temporal response properties (shorter temporal delays) compared to a uniform distribution. Specifically, these kernels converge very rapidly to a limit kernel possessing true self-similar scale-invariant properties over temporal scales, thereby allowing for true scale invariance over variations in the temporal scale, although the underlying temporal scale-space representation is based on a discretized temporal scale parameter. We show how scale-normalized temporal derivatives can be defined for these time-causal scale-space kernels and how the composed theory can be used for computing basic types of scale-normalized spatio-temporal derivative expressions in a computationally efficient manner.

##### Abstract (translated by Google)
我们提出了一个改进的时间 - 因果和时间递归时空感受场的模型和理论，基于空间域上的高斯接受场和一阶积分器或等效截断指数滤波器在时域上级联耦合。与以前的时空尺度空间公式相比，在非增强局部极值或尺度不变性方面，这些接受场是基于不同尺度空间公理的，随着时间的推移，通过确保不产生新的局部极值或零交叉增加时间尺度。具体而言，扩展是关于（i）参数化中间时间尺度水平，（ii）分析所产生的时间动态，（iii）将理论转移到离散实现，（iv）计算比例归一化的时空导数表达式（v）生物视觉中外侧膝状体核（LGN）和初级视觉皮层（V1）中感受野的计算模型。我们表明，通过按照对数分布分布中间时间尺度水平，与均匀分布相比，我们获得更快的时间响应性质（更短的时间延迟）。具体来说，这些核很快收敛到一个极限核，在时间尺度上具有真正的自相似尺度不变特性，从而允许真正的尺度不变性超过时间尺度的变化，虽然基础时间尺度空间表示是基于离散化时间尺度参数。我们展示了如何为这些时间 - 因果尺度空间内核定义尺度标准化的时间导数，以及如何使用组合理论以计算有效的方式计算尺度标准化的时空导数表达式的基本类型。

##### URL
[https://arxiv.org/abs/1504.02648](https://arxiv.org/abs/1504.02648)

##### PDF
[https://arxiv.org/pdf/1504.02648](https://arxiv.org/pdf/1504.02648)

