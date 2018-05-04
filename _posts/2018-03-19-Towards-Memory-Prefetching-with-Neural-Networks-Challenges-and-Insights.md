---
layout: post
title: "Towards Memory Prefetching with Neural Networks: Challenges and Insights"
date: 2018-03-19 12:56:04
categories: arXiv_CV
tags: arXiv_CV Relation Recognition
author: Leeor Peled, Uri Weiser, Yoav Etsion
mathjax: true
---

* content
{:toc}

##### Abstract
Accurate memory prefetching is paramount for processor performance, and modern processors employ various techniques to identify and prefetch different memory access patterns. While most modern prefetchers target spatio-temporal patterns by matching memory addresses that are accessed in close proximity (either in space or time), the recently proposed concept of semantic locality views locality as an artifact of the algorithmic level and searches for correlations between memory accesses and program state. While this approach was shown to be effective, capturing semantic locality requires significant associative learning capabilities. In this paper we utilize neural networks for this task. Artificial neural networks are becoming increasingly effective in tasks of pattern recognition and associative learning of complex relations. We leverage recent advances in this field to propose a conceptual neural network prefetcher. We show that by targeting semantic locality, this prefetcher can learn distinct memory access patterns that cannot be covered by other state-of-the-art prefetchers. We evaluate the neural network prefetcher over SPEC2006, Graph500, and a variety of handwritten kernels. We show that the prefetcher can deliver an average speedup of 22% for SPEC2006 (up to 90%) and up to 5x over kernels. We also explore the limitations of using neural networks for prefetching. Ultimately, we conclude that although there are still many challenges to overcome before we can reach a feasible, power-efficient implementation, the neural network prefetcher potential gains over state-of-the-art prefetchers justify further exploration

##### Abstract (translated by Google)
准确的内存预取对处理器性能至关重要，现代处理器采用各种技术来识别和预取不同的内存访问模式。虽然大多数现代的预取器通过匹配非常接近（空间或时间）访问的内存地址来定位时空模式，但最近提出的语义局部性概念将局部性视为算法级别的伪像，并搜索内存访问之间的相关性和程序状态。虽然这种方法被证明是有效的，但捕获语义位置需要显着的关联学习能力。在本文中，我们利用神经网络来完成这项任务。人工神经网络在复杂关系的模式识别和关联学习任务中变得越来越有效。我们利用这一领域的最新进展来提出概念性神经网络预取器。我们证明，通过针对语义位置，这个预取器可以学习其他先进的预取程序无法覆盖的不同内存访问模式。我们通过SPEC2006，Graph500和各种手写内核来评估神经网络预取器。我们展示了预取器可以为SPEC2006提供22％的平均加速（高达90％），并且可以在内核上提高5倍。我们还探讨了使用神经网络进行预取的局限性。最终，我们得出结论：虽然在我们能够实现可行的节能实现之前还有许多挑战需要克服，但是神经网络预取器相对于最先进的预取器的潜在收益证明了其进一步探索的合理性

##### URL
[https://arxiv.org/abs/1804.00478](https://arxiv.org/abs/1804.00478)

##### PDF
[https://arxiv.org/pdf/1804.00478](https://arxiv.org/pdf/1804.00478)

