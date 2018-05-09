---
layout: post
title: "Online normalizer calculation for softmax"
date: 2018-05-08 07:34:17
categories: arXiv_AI
tags: arXiv_AI
author: Maxim Milakov (NVIDIA), Natalia Gimelshein (NVIDIA)
mathjax: true
---

* content
{:toc}

##### Abstract
The Softmax function is ubiquitous in machine learning, multiple previous works suggested faster alternatives for it. In this paper we propose a way to compute classical Softmax with fewer memory accesses and hypothesize that this reduction in memory accesses should improve Softmax performance on actual hardware. The benchmarks confirm this hypothesis: Softmax accelerates by up to 1.3x and Softmax+TopK combined by up to 5x.

##### Abstract (translated by Google)
Softmax功能在机器学习中无处不在，以前的多个作品为其提供了更快的选择。在本文中，我们提出了一种用更少的存储器访问来计算经典Softmax的方法，并且假设存储器访问的这种减少应该会改善实际硬件上的Softmax性能。基准证实了这一假设：Softmax加速高达1.3倍，Softmax + TopK加起来高达5倍。

##### URL
[https://arxiv.org/abs/1805.02867](https://arxiv.org/abs/1805.02867)

##### PDF
[https://arxiv.org/pdf/1805.02867](https://arxiv.org/pdf/1805.02867)

