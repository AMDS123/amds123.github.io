---
layout: post
title: "Decoding Generalized Reed-Solomon Codes and Its Application to RLCE Encryption Schemes"
date: 2017-07-30 04:42:27
categories: arXiv_CV
tags: arXiv_CV
author: Yongge Wang
mathjax: true
---

* content
{:toc}

##### Abstract
This paper compares the efficiency of various algorithms for implementing quantum resistant public key encryption scheme RLCE on 64-bit CPUs. By optimizing various algorithms for polynomial and matrix operations over finite fields, we obtained several interesting (or even surprising) results. For example, it is well known (e.g., Moenck 1976 \cite{moenck1976practical}) that Karatsuba's algorithm outperforms classical polynomial multiplication algorithm from the degree 15 and above (practically, Karatsuba's algorithm only outperforms classical polynomial multiplication algorithm from the degree 35 and above ). Our experiments show that 64-bit optimized Karatsuba's algorithm will only outperform 64-bit optimized classical polynomial multiplication algorithm for polynomials of degree 115 and above over finite field $GF(2^{10})$. The second interesting (surprising) result shows that 64-bit optimized Chien's search algorithm ourperforms all other 64-bit optimized polynomial root finding algorithms such as BTA and FFT for polynomials of all degrees over finite field $GF(2^{10})$. The third interesting (surprising) result shows that 64-bit optimized Strassen matrix multiplication algorithm only outperforms 64-bit optimized classical matrix multiplication algorithm for matrices of dimension 750 and above over finite field $GF(2^{10})$. It should be noted that existing literatures and practices recommend Strassen matrix multiplication algorithm for matrices of dimension 40 and above. All our experiments are done on a 64-bit MacBook Pro with i7 CPU and single thread C codes. It should be noted that the reported results should be appliable to 64 or larger bits CPU architectures. For 32 or smaller bits CPUs, these results may not be applicable. The source code and library for the algorithms covered in this paper are available at this http URL.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1702.07737](https://arxiv.org/abs/1702.07737)

##### PDF
[https://arxiv.org/pdf/1702.07737](https://arxiv.org/pdf/1702.07737)

