---
layout: post
title: "AI Matrix - Synthetic Benchmarks for DNN"
date: 2018-11-27 19:20:35
categories: arXiv_AI
tags: arXiv_AI CNN
author: Wei Wei, Lingjie Xu, Lingling Jin, Wei Zhang, Tianjun Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural network (DNN) architectures, such as convolutional neural networks (CNN), involve heavy computation and require hardware, such as CPU, GPU, and AI accelerators, to provide the massive computing power. With the many varieties of AI hardware prevailing on the market, it is often hard to decide which one is the best to use. Thus, benchmarking AI hardware effectively becomes important and is of great help to select and optimize AI hardware. Unfortunately, there are few AI benchmarks available in both academia and industry. Examples are BenchNN[1], DeepBench[2], and Dawn Bench[3], which are usually a collection of typical real DNN applications. While these benchmarks provide performance comparison across different AI hardware, they suffer from a number of drawbacks. First, they cannot adapt to the emerging changes of DNN algorithms and are fixed once selected. Second, they contain tens to hundreds of applications and take very long time to finish running. Third, they are mainly selected from open sources, which are restricted by copyright and are not representable to proprietary applications. In this work, a synthetic benchmarks framework is firstly proposed to address the above drawbacks of AI benchmarks. Instead of pre-selecting a set of open-sourced benchmarks and running all of them, the synthetic approach generates only a one or few benchmarks that best represent a broad range of applications using profiled workload characteristics data of these applications. Thus, it can adapt to emerging changes of new DNN algorithms by re-profiling new applications and updating itself, greatly reduce benchmark count and running time, and strongly represent DNN applications of interests. The generated benchmarks are called AI Matrix, serving as a performance benchmarks matching the statistical workload characteristics of a combination of applications of interests.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.00886](http://arxiv.org/abs/1812.00886)

##### PDF
[http://arxiv.org/pdf/1812.00886](http://arxiv.org/pdf/1812.00886)

