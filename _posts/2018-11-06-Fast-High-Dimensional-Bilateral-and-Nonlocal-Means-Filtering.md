---
layout: post
title: "Fast High-Dimensional Bilateral and Nonlocal Means Filtering"
date: 2018-11-06 14:20:35
categories: arXiv_CV
tags: arXiv_CV
author: Pravin Nair, Kunal. N. Chaudhury
mathjax: true
---

* content
{:toc}

##### Abstract
Existing fast algorithms for bilateral and nonlocal means filtering mostly work with grayscale images. They cannot easily be extended to high-dimensional data such as color and hyperspectral images, patch-based data, flow-fields, etc. In this paper, we propose a fast algorithm for high-dimensional bilateral and nonlocal means filtering. Unlike existing approaches, where the focus is on approximating the data (using quantization) or the filter kernel (via analytic expansions), we locally approximate the kernel using weighted and shifted copies of a Gaussian, where the weights and shifts are inferred from the data. The algorithm emerging from the proposed approximation essentially involves clustering and fast convolutions, and is easy to implement. Moreover, a variant of our algorithm comes with a guarantee (bound) on the approximation error, which is not enjoyed by existing algorithms. We present some results for high-dimensional bilateral and nonlocal means filtering to demonstrate the speed and accuracy of our proposal. Moreover, we also show that our algorithm can outperform state-of-the-art fast approximations in terms of accuracy and timing.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1811.02363](https://arxiv.org/abs/1811.02363)

##### PDF
[https://arxiv.org/pdf/1811.02363](https://arxiv.org/pdf/1811.02363)

