---
layout: post
title: "The Indirect Convolution Algorithm"
date: 2019-07-03 20:51:18
categories: arXiv_CV
tags: arXiv_CV Face Deep_Learning
author: Marat Dukhan
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning frameworks commonly implement convolution operators with GEMM-based algorithms. In these algorithms, convolution is implemented on top of matrix-matrix multiplication (GEMM) functions, provided by highly optimized BLAS libraries. Convolutions with 1x1 kernels can be directly represented as a GEMM call, but convolutions with larger kernels require a special memory layout transformation - im2col or im2row - to fit into GEMM interface. 
 The Indirect Convolution algorithm provides the efficiency of the GEMM primitive without the overhead of im2col transformation. In contrast to GEMM-based algorithms, the Indirect Convolution does not reshuffle the data to fit into the GEMM primitive but introduces an indirection buffer - a buffer of pointers to the start of each row of image pixels. This broadens the application of our modified GEMM function to convolutions with arbitrary kernel size, padding, stride, and dilation. 
 The Indirect Convolution algorithm reduces memory overhead proportionally to the number of input channels and outperforms the GEMM-based algorithm by up to 62% on convolution parameters which involve im2col transformations in GEMM-based algorithms. This, however, comes at cost of minor performance reduction on 1x1 stride-1 convolutions.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.02129](http://arxiv.org/abs/1907.02129)

##### PDF
[http://arxiv.org/pdf/1907.02129](http://arxiv.org/pdf/1907.02129)

