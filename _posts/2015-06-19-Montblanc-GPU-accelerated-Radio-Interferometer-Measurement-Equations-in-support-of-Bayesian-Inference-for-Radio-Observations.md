---
layout: post
title: "Montblanc: GPU accelerated Radio Interferometer Measurement Equations in support of Bayesian Inference for Radio Observations"
date: 2015-06-19 11:52:12
categories: arXiv_CV
tags: arXiv_CV Inference
author: Simon Perkins, Patrick Marais, Jonathan Zwart, Iniyan Natarajan, Cyril Tasse, Oleg Smirnov
mathjax: true
---

* content
{:toc}

##### Abstract
We present Montblanc, a GPU implementation of the Radio interferometer measurement equation (RIME) in support of the Bayesian inference for radio observations (BIRO) technique. BIRO uses Bayesian inference to select sky models that best match the visibilities observed by a radio interferometer. To accomplish this, BIRO evaluates the RIME multiple times, varying sky model parameters to produce multiple model visibilities. Chi-squared values computed from the model and observed visibilities are used as likelihood values to drive the Bayesian sampling process and select the best sky model. As most of the elements of the RIME and chi-squared calculation are independent of one another, they are highly amenable to parallel computation. Additionally, Montblanc caters for iterative RIME evaluation to produce multiple chi-squared values. Modified model parameters are transferred to the GPU between each iteration. We implemented Montblanc as a Python package based upon NVIDIA's CUDA architecture. As such, it is easy to extend and implement different pipelines. At present, Montblanc supports point and Gaussian morphologies, but is designed for easy addition of new source profiles. Montblanc's RIME implementation is performant: On an NVIDIA K40, it is approximately 250 times faster than MeqTrees on a dual hexacore Intel E5-2620v2 CPU. Compared to the OSKAR simulator's GPU-implemented RIME components it is 7.7 and 12 times faster on the same K40 for single and double-precision floating point respectively. However, OSKAR's RIME implementation is more general than Montblanc's BIRO-tailored RIME. Theoretical analysis of Montblanc's dominant CUDA kernel suggests that it is memory bound. In practice, profiling shows that is balanced between compute and memory, as much of the data required by the problem is retained in L1 and L2 cache.

##### Abstract (translated by Google)
我们提出了Montblanc，一种支持无线电观测贝叶斯推断（BIRO）技术的无线电干涉仪测量方程（RIME）的GPU实现。 BIRO使用贝叶斯推断来选择最适合无线电干涉仪观测到的可见度的天空模型。为此，BIRO多次评估RIME，改变天空模型参数以产生多个模型可见度。由模型计算的卡方值和观测的可见度被用作可能性值以推动贝叶斯采样过程并选择最佳的天空模型。由于RIME和卡方计算的大部分元素是相互独立的，因此它们非常适合并行计算。此外，万宝龙迎合迭代RIME评估产生多个卡方值。在每次迭代之间，修改的模型参数被传送到GPU。我们将Montblanc作为基于NVIDIA CUDA架构的Python软件包实现。因此，扩展和实现不同的管道是很容易的。目前，万宝龙支持点和高斯形态，但设计容易添加新的源配置文件。万宝龙的RIME实现是高性能的：在NVIDIA K40上，它比MeqTrees在双六进制英特尔E5-2620v2 CPU上快大约250倍。与OSKAR仿真器的GPU实现的RIME组件相比，相同的K40对于单精度和双精度浮点分别为7.7和12倍。然而，OSKAR的RIME实现比万宝龙的BIRO量身定制的RIME更普遍。对万宝龙的主导CUDA内核的理论分析表明，它是内存约束。在实践中，性能分析显示在计算和内存之间是平衡的，因为问题所需的大部分数据都保留在L1和L2缓存中。

##### URL
[https://arxiv.org/abs/1501.07719](https://arxiv.org/abs/1501.07719)

##### PDF
[https://arxiv.org/pdf/1501.07719](https://arxiv.org/pdf/1501.07719)

