---
layout: post
title: "HPTT: A High-Performance Tensor Transposition C++ Library"
date: 2017-05-10 21:34:51
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Paul Springer, Tong Su, Paolo Bientinesi
mathjax: true
---

* content
{:toc}

##### Abstract
Recently we presented TTC, a domain-specific compiler for tensor transpositions. Despite the fact that the performance of the generated code is nearly optimal, due to its offline nature, TTC cannot be utilized in all the application codes in which the tensor sizes and the necessary tensor permutations are determined at runtime. To overcome this limitation, we introduce the open-source C++ library High-Performance Tensor Transposition (HPTT). Similar to TTC, HPTT incorporates optimizations such as blocking, multi-threading, and explicit vectorization; furthermore it decomposes any transposition into multiple loops around a so called micro-kernel. This modular design---inspired by BLIS---makes HPTT easy to port to different architectures, by only replacing the hand-vectorized micro-kernel (e.g., a 4x4 transpose). HPTT also offers an optional autotuning framework---guided by a performance model---that explores a vast search space of implementations at runtime (similar to FFTW). Across a wide range of different tensor transpositions and architectures (e.g., Intel Ivy Bridge, Intel Knights Landing, ARMv7, IBM Power7), HPTT attains a bandwidth comparable to that of SAXPY, and yields remarkable speedups over Eigen's tensor transposition implementation. Most importantly, the integration of HPTT into the Cyclops Tensor Framework (CTF) improves the overall performance of tensor contractions by up to 3.1x.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1704.04374](https://arxiv.org/abs/1704.04374)

##### PDF
[https://arxiv.org/pdf/1704.04374](https://arxiv.org/pdf/1704.04374)

