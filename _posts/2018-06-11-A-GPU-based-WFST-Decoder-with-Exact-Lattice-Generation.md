---
layout: post
title: "A GPU-based WFST Decoder with Exact Lattice Generation"
date: 2018-06-11 00:10:54
categories: arXiv_CL
tags: arXiv_CL Recognition
author: Zhehuai Chen, Justin Luitjens, Hainan Xu, Yiming Wang, Daniel Povey, Sanjeev Khudanpur
mathjax: true
---

* content
{:toc}

##### Abstract
We describe initial work on an extension of the Kaldi toolkit that supports weighted finite-state transducer (WFST) decoding on Graphics Processing Units (GPUs). We implement token recombination as an atomic GPU operation in order to fully parallelize the Viterbi beam search, and propose a dynamic load balancing strategy for more efficient token passing scheduling among GPU threads. We also redesign the exact lattice generation and lattice pruning algorithms for better utilization of the GPUs. Experiments on the Switchboard corpus show that the proposed method achieves identical 1-best results and lattice quality in recognition and confidence measure tasks, while running 3 to 15 times faster than the single process Kaldi decoder. The above results are reported on different GPU architectures. Additionally we obtain a 46-fold speedup with sequence parallelism and multi-process service (MPS) in GPU.

##### Abstract (translated by Google)
我们描述了支持在图形处理单元（GPU）上支持加权有限状态转换器（WFST）解码的Kaldi工具包扩展的初始工作。为了完全并行化维特比波束搜索，我们实现了令牌重组作为原子GPU操作，并提出了一种动态负载平衡策略，用于GPU线程之间更有效的令牌传递调度。我们还重新设计了确切的格阵生成和格修剪算法，以更好地利用GPU。在交换机语料库上的实验表明，所提出的方法在识别和置信度测量任务中实现相同的1最佳结果和点阵质量，而运行速度比单个过程Kaldi解码器快3到15倍。上述结果在不同的GPU架构上报告。另外我们在GPU中获得了序列并行性和多进程服务（MPS）的46倍加速。

##### URL
[http://arxiv.org/abs/1804.03243](http://arxiv.org/abs/1804.03243)

##### PDF
[http://arxiv.org/pdf/1804.03243](http://arxiv.org/pdf/1804.03243)

