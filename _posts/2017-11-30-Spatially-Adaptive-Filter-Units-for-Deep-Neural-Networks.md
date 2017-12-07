---
layout: post
title: "Spatially-Adaptive Filter Units for Deep Neural Networks"
date: 2017-11-30 15:49:13
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Classification
author: Domen Tabernik, Matej Kristan, Aleš Leonardis
mathjax: true
---

* content
{:toc}

##### Abstract
Classical deep convolutional networks increase receptive field size by either gradual resolution reduction or application of hand-crafted dilated convolutions to prevent increase in the number of parameters. In this paper we propose a novel displaced aggregation unit (DAU) that does not require hand-crafting. In contrast to classical filters with units (pixels) placed on a fixed regular grid, the displacement of the DAUs are learned, which enables filters to spatially-adapt their receptive field to a given problem. We extensively demonstrate the strength of DAUs on a classification and semantic segmentation tasks. Compared to ConvNets with regular filter, ConvNets with DAUs achieve comparable performance at faster convergence and up to 3-times reduction in parameters. Furthermore, DAUs allow us to study deep networks from novel perspectives. We study spatial distributions of DAU filters and analyze the number of parameters allocated for spatial coverage in a filter.

##### Abstract (translated by Google)
经典的深度卷积网络通过逐渐降低分辨率或应用手工扩张卷积来增加感受野大小，以防止参数数量的增加。在本文中，我们提出了一种不需要手工操作的新型置换聚合单元（DAU）。与单位（像素）放置在固定规则网格上的经典滤波器相反，DAU的位移被学习到，这使得滤波器能够在空间上使其接收场与给定问题相适应。我们广泛地展示了DAU在分类和语义分割任务上的优势。与具有常规过滤器的ConvNet相比，带有DAU的ConvNets在收敛速度更快，参数减少3倍的情况下实现了可比较的性能。此外，DAU允许我们从新的角度研究深度网络。我们研究DAU过滤器的空间分布，并分析过滤器中分配给空间覆盖的参数的数量。

##### URL
[https://arxiv.org/abs/1711.11473](https://arxiv.org/abs/1711.11473)

##### PDF
[https://arxiv.org/pdf/1711.11473](https://arxiv.org/pdf/1711.11473)

