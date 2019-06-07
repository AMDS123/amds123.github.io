---
layout: post
title: "Butterfly Transform: An Efficient FFT Based Neural Architecture Design"
date: 2019-06-05 19:04:06
categories: arXiv_CV
tags: arXiv_CV NAS
author: Keivan Alizadeh, Ali Farhadi, Mohammad Rastegari
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we introduce the Butterfly Transform (BFT), a light weight channel fusion method that reduces the computational complexity of point-wise convolutions from O(n^2) of conventional solutions to O(n log n) with respect to the number of channels while improving the accuracy of the networks under the same range of FLOPs. The proposed BFT generalizes the Discrete Fourier Transform in a way that its parameters are learned at training time. Our experimental evaluations show that replacing channel fusion modules with \sys results in significant accuracy gains at similar FLOPs across a wide range of network architectures. For example, replacing channel fusion convolutions with BFT offers 3% absolute top-1 improvement for MobileNetV1-0.25 and 2.5% for ShuffleNet V2-0.5 while maintaining the same number of FLOPS. Notably, the ShuffleNet-V2+BFT outperforms state-of-the-art architecture search methods MNasNet \cite{tan2018mnasnet} and FBNet \cite{wu2018fbnet}. We also show that the structure imposed by BFT has interesting properties that ensures the efficacy of the resulting network.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1906.02256](https://arxiv.org/abs/1906.02256)

##### PDF
[https://arxiv.org/pdf/1906.02256](https://arxiv.org/pdf/1906.02256)

