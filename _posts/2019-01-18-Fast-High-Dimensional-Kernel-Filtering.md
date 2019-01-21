---
layout: post
title: "Fast High-Dimensional Kernel Filtering"
date: 2019-01-18 07:24:28
categories: arXiv_CV
tags: arXiv_CV
author: Pravin Nair, Kunal N. Chaudhury
mathjax: true
---

* content
{:toc}

##### Abstract
The bilateral and nonlocal means filters are instances of kernel-based filters that are popularly used in image processing. It was recently shown that fast and accurate bilateral filtering of grayscale images can be performed using a low-rank approximation of the kernel matrix. More specifically, based on the eigendecomposition of the kernel matrix, the overall filtering was approximated using spatial convolutions, for which efficient algorithms are available. Unfortunately, this technique cannot be scaled to high-dimensional data such as color and hyperspectral images. This is simply because one needs to compute/store a large matrix and perform its eigendecomposition in this case. We show how this problem can be solved using the Nystr\"om method, which is generally used for approximating the eigendecomposition of large matrices. The resulting algorithm can also be used for nonlocal means filtering. We demonstrate the effectiveness of our proposal for bilateral and nonlocal means filtering of color and hyperspectral images. In particular, our method is shown to be competitive with state-of-the-art fast algorithms, and moreover it comes with a theoretical guarantee on the approximation error.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.06112](http://arxiv.org/abs/1901.06112)

##### PDF
[http://arxiv.org/pdf/1901.06112](http://arxiv.org/pdf/1901.06112)

