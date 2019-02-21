---
layout: post
title: "DNNVM : End-to-End Compiler Leveraging Heterogeneous Optimizations on FPGA-based CNN Accelerators"
date: 2019-02-20 09:30:17
categories: arXiv_CV
tags: arXiv_CV CNN Optimization Deep_Learning
author: Yu Xing, Shuang Liang, Lingzhi Sui, Xijie Jia, Jiantao Qiu, Xin Liu, Yushun Wang, Yu Wang, Yi Shan
mathjax: true
---

* content
{:toc}

##### Abstract
The convolutional neural network (CNN) has become a state-of-the-art method for several artificial intelligence domains in recent years. The increasingly complex CNN models are both computation-bound and I/O-bound. FPGA-based accelerators driven by custom instruction set architecture (ISA) achieve a balance between generality and efficiency, but there is much on them left to be optimized. We propose the full-stack compiler DNNVM, which is an integration of optimizers for graphs, loops and data layouts, and an assembler, a runtime supporter and a validation environment. The DNNVM works in the context of deep learning frameworks and transforms CNN models into the directed acyclic graph: XGraph. Based on XGraph, we transform the optimization challenges for both the data layout and pipeline into graph-level problems. DNNVM enumerates all potentially profitable fusion opportunities by a heuristic subgraph isomorphism algorithm to leverage pipeline and data layout optimizations, and searches for the optimal execution strategies of the whole computing graph. On the Xilinx ZU2 @330 MHz and ZU9 @330 MHz, we achieve equivalently state-of-the-art performance on our benchmarks by naive implementations without optimizations, and the throughput is further improved up to 1.26x by leveraging heterogeneous optimizations in DNNVM. Finally, with ZU9 @330 MHz, we achieve state-of-the-art performance for VGG and ResNet50. We achieve a throughput of 2.82 TOPs/s and an energy efficiency of 123.7 GOPs/s/W for VGG. Additionally, we achieve 1.38 TOPs/s for ResNet50.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.07463](http://arxiv.org/abs/1902.07463)

##### PDF
[http://arxiv.org/pdf/1902.07463](http://arxiv.org/pdf/1902.07463)

