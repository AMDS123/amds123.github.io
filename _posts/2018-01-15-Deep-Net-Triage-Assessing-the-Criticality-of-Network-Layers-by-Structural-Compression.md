---
layout: post
title: "Deep Net Triage: Assessing the Criticality of Network Layers by Structural Compression"
date: 2018-01-15 03:04:18
categories: arXiv_CV
tags: arXiv_CV
author: Theodore S. Nowak, Jason J. Corso
mathjax: true
---

* content
{:toc}

##### Abstract
Deep network compression seeks to reduce the number of parameters in the network while maintaining a certain level of performance. Deep network distillation seeks to train a smaller network that matches soft-max performance of a larger network. While both regimes have led to impressive performance for their respective goals, neither provide insight into the importance of a given layer in the original model, which is useful if we are to improve our understanding of these highly parameterized models. In this paper, we present the concept of deep net triage, which individually assesses small blocks of convolution layers to understand their collective contribution to the overall performance, which we call criticality. We call it triage because we assess this criticality by answering the question: what is the impact to the health of the overall network if we compress a block of layers into a single layer. We propose a suite of triage methods and compare them on problem spaces of varying complexity. We ultimately show that, across these problem spaces, deep net triage is able to indicate the of relative importance of different layers. Surprisingly, our local structural compression technique also leads to an improvement in overall accuracy when the final model is fine-tuned globally.

##### Abstract (translated by Google)
深度网络压缩旨在减少网络中的参数数量，同时保持一定的性能水平。深度网络蒸馏试图训练与更大网络的软最大性能匹配的更小的网络。虽然这两个制度都为各自的目标带来了令人印象深刻的业绩，但是如果我们要提高对这些高度参数化模型的理解，那么既不能提供对原始模型中给定层的重要性的认识。在本文中，我们提出深度分类的概念，它们分别评估卷积层的小块，以了解它们对总体性能的集体贡献，我们称之为临界性。我们把它称为分流，因为我们通过回答这个问题来评估这个关键性：如果我们将一个图层块压缩成一个单层，那么对整个网络的健康有什么影响？我们提出了一套分类方法，并将其与不同复杂度的问题空间进行比较。我们最终表明，在这些问题空间中，深度分类能够指示不同层次的相对重要性。令人惊讶的是，当最终模型在全球范围内进行微调时，我们的局部结构压缩技术也导致整体精度的提高。

##### URL
[https://arxiv.org/abs/1801.04651](https://arxiv.org/abs/1801.04651)

##### PDF
[https://arxiv.org/pdf/1801.04651](https://arxiv.org/pdf/1801.04651)

