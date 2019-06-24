---
layout: post
title: "Backpropagation-Friendly Eigendecomposition"
date: 2019-06-21 09:17:14
categories: arXiv_CV
tags: arXiv_CV
author: Wei Wang, Zheng Dang, Yinlin Hu, Pascal Fua, Mathieu Salzmann
mathjax: true
---

* content
{:toc}

##### Abstract
Eigendecomposition (ED) is widely used in deep networks. However, the backpropagation of its results tends to be numerically unstable, whether using ED directly or approximating it with the Power Iteration method, particularly when dealing with large matrices. While this can be mitigated by partitioning the data in small and arbitrary groups, doing so has no theoretical basis and makes its impossible to exploit the power of ED to the full. In this paper, we introduce a numerically stable and differentiable approach to leveraging eigenvectors in deep networks. It can handle large matrices without requiring to split them. We demonstrate the better robustness of our approach over standard ED and PI for ZCA whitening, an alternative to batch normalization, and for PCA denoising, which we introduce as a new normalization strategy for deep networks, aiming to further denoise the network's features.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.09023](http://arxiv.org/abs/1906.09023)

##### PDF
[http://arxiv.org/pdf/1906.09023](http://arxiv.org/pdf/1906.09023)

