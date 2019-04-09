---
layout: post
title: "Iterative Normalization: Beyond Standardization towards Efficient Whitening"
date: 2019-04-06 13:10:20
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Lei Huang, Yi Zhou, Fan Zhu, Li Liu, Ling Shao
mathjax: true
---

* content
{:toc}

##### Abstract
Batch Normalization (BN) is ubiquitously employed for accelerating neural network training and improving the generalization capability by performing standardization within mini-batches. Decorrelated Batch Normalization (DBN) further boosts the above effectiveness by whitening. However, DBN relies heavily on either a large batch size, or eigen-decomposition that suffers from poor efficiency on GPUs. We propose Iterative Normalization (IterNorm), which employs Newton's iterations for much more efficient whitening, while simultaneously avoiding the eigen-decomposition. Furthermore, we develop a comprehensive study to show IterNorm has better trade-off between optimization and generalization, with theoretical and experimental support. To this end, we exclusively introduce Stochastic Normalization Disturbance (SND), which measures the inherent stochastic uncertainty of samples when applied to normalization operations. With the support of SND, we provide natural explanations to several phenomena from the perspective of optimization, e.g., why group-wise whitening of DBN generally outperforms full-whitening and why the accuracy of BN degenerates with reduced batch sizes. We demonstrate the consistently improved performance of IterNorm with extensive experiments on CIFAR-10 and ImageNet over BN and DBN.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.03441](http://arxiv.org/abs/1904.03441)

##### PDF
[http://arxiv.org/pdf/1904.03441](http://arxiv.org/pdf/1904.03441)

