---
layout: post
title: "Automating the Last-Mile for High Performance Dense Linear Algebra"
date: 2017-04-28 15:22:19
categories: arXiv_CV
tags: arXiv_CV
author: Richard Michael Veras, Tze Meng Low, Tyler Michael Smith, Robert van de Geijn, Franz Franchetti
mathjax: true
---

* content
{:toc}

##### Abstract
High performance dense linear algebra (DLA) libraries often rely on a general matrix multiply (Gemm) kernel that is implemented using assembly or with vector intrinsics. In particular, the real-valued Gemm kernels provide the overwhelming fraction of performance for the complex-valued Gemm kernels, along with the entire level-3 BLAS and many of the real and complex LAPACK routines. Thus,achieving high performance for the Gemm kernel translates into a high performance linear algebra stack above this kernel. However, it is a monumental task for a domain expert to manually implement the kernel for every library-supported architecture. This leads to the belief that the craft of a Gemm kernel is more dark art than science. It is this premise that drives the popularity of autotuning with code generation in the domain of DLA. This paper, instead, focuses on an analytical approach to code generation of the Gemm kernel for different architecture, in order to shed light on the details or voo-doo required for implementing a high performance Gemm kernel. We distill the implementation of the kernel into an even smaller kernel, an outer-product, and analytically determine how available SIMD instructions can be used to compute the outer-product efficiently. We codify this approach into a system to automatically generate a high performance SIMD implementation of the Gemm kernel. Experimental results demonstrate that our approach yields generated kernels with performance that is competitive with kernels implemented manually or using empirical search.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1611.08035](https://arxiv.org/abs/1611.08035)

##### PDF
[https://arxiv.org/pdf/1611.08035](https://arxiv.org/pdf/1611.08035)

