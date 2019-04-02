---
layout: post
title: "Single Path One-Shot Neural Architecture Search with Uniform Sampling"
date: 2019-03-31 14:34:43
categories: arXiv_CV
tags: arXiv_CV
author: Zichao Guo, Xiangyu Zhang, Haoyuan Mu, Wen Heng, Zechun Liu, Yichen Wei, Jian Sun
mathjax: true
---

* content
{:toc}

##### Abstract
One-shot method is a powerful Neural Architecture Search (NAS) framework, but its training is non-trivial and it is difficult to achieve competitive results on large scale datasets like ImageNet. In this work, we propose a Single Path One-Shot model to address its main challenge in the training. Our central idea is to construct a simplified supernet, Single Path Supernet, which is trained by an uniform path sampling method. All underlying architectures (and their weights) get trained fully and equally. Once we have a trained supernet, we apply an evolutionary algorithm to efficiently search the best-performing architectures without any fine tuning. Comprehensive experiments verify that our approach is flexible and effective. It is easy to train and fast to search. It effortlessly supports complex search spaces (e.g., building blocks, channel, mixed-precision quantization) and different search constraints (e.g., FLOPs, latency). It is thus convenient to use for various needs. It achieves start-of-the-art performance on the large dataset ImageNet.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.00420](http://arxiv.org/abs/1904.00420)

##### PDF
[http://arxiv.org/pdf/1904.00420](http://arxiv.org/pdf/1904.00420)

