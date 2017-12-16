---
layout: post
title: "Optimal DNN Primitive Selection with Partitioned Boolean Quadratic Programming"
date: 2017-10-03 11:25:24
categories: arXiv_CV
tags: arXiv_CV Embedding Inference
author: Andrew Anderson, David Gregg
mathjax: true
---

* content
{:toc}

##### Abstract
Deep Neural Networks (DNNs) require very large amounts of computation both for training and for inference when deployed in the field. Many different algorithms have been proposed to implement the most computationally expensive layers of DNNs. Further, each of these algorithms has a large number of variants, which offer different trade-offs of parallelism, data locality, memory footprint, and execution time. In addition, specific algorithms operate much more efficiently on specialized data layouts and formats. We state the problem of optimal primitive selection in the presence of data format transformations, and show that it is NP-hard by demonstrating an embedding in the Partitioned Boolean Quadratic Assignment problem (PBQP). We propose an analytic solution via a PBQP solver, and evaluate our approach experimentally by optimizing several popular DNNs using a library of more than 70 DNN primitives, on an embedded platform and a general purpose platform. We show experimentally that significant gains are possible versus the state of the art vendor libraries by using a principled analytic solution to the problem of layout selection in the presence of data format transformations.

##### Abstract (translated by Google)
深度神经网络（DNN）在现场部署时需要进行大量的训练和推理计算。已经提出了许多不同的算法来实现最计算量的DNN层。此外，这些算法中的每一个都有大量的变体，它们提供了不同的并行性，数据局部性，内存占用和执行时间的权衡。另外，特定的算法可以更有效地处理专门的数据布局和格式。在存在数据格式转换的情况下，我们陈述了最优基元选择的问题，并通过在分区布尔二次分配问题（PBQP）中演示嵌入来证明它是NP难的。我们通过PBQP求解器提出了一个分析解决方案，并通过在嵌入式平台和通用平台上使用超过70个DNN基元的库优化几个流行的DNN来实验性地评估我们的方法。我们通过实验显示，通过使用数据格式转换时存在的布局选择问题的原理性分析解决方案，与现有技术的供应商库相比，显着的收益是可能的。

##### URL
[https://arxiv.org/abs/1710.01079](https://arxiv.org/abs/1710.01079)

##### PDF
[https://arxiv.org/pdf/1710.01079](https://arxiv.org/pdf/1710.01079)

