---
layout: post
title: "A GPU-based WFST Decoder with Exact Lattice Generation"
date: 2018-07-27 08:46:50
categories: arXiv_CV
tags: arXiv_CV Recognition
author: Zhehuai Chen, Justin Luitjens, Hainan Xu, Yiming Wang, Daniel Povey, Sanjeev Khudanpur
mathjax: true
---

* content
{:toc}

##### Abstract
We describe initial work on an extension of the Kaldi toolkit that supports weighted finite-state transducer (WFST) decoding on Graphics Processing Units (GPUs). We implement token recombination as an atomic GPU operation in order to fully parallelize the Viterbi beam search, and propose a dynamic load balancing strategy for more efficient token passing scheduling among GPU threads. We also redesign the exact lattice generation and lattice pruning algorithms for better utilization of the GPUs. Experiments on the Switchboard corpus show that the proposed method achieves identical 1-best results and lattice quality in recognition and confidence measure tasks, while running 3 to 15 times faster than the single process Kaldi decoder. The above results are reported on different GPU architectures. Additionally we obtain a 46-fold speedup with sequence parallelism and multi-process service (MPS) in GPU.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1804.03243](https://arxiv.org/abs/1804.03243)

##### PDF
[https://arxiv.org/pdf/1804.03243](https://arxiv.org/pdf/1804.03243)

