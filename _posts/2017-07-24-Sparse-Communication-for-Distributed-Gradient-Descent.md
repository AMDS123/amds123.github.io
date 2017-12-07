---
layout: post
title: "Sparse Communication for Distributed Gradient Descent"
date: 2017-07-24 21:47:51
categories: arXiv_CL
tags: arXiv_CL NMT Gradient_Descent
author: Alham Fikri Aji, Kenneth Heafield
mathjax: true
---

* content
{:toc}

##### Abstract
We make distributed stochastic gradient descent faster by exchanging sparse updates instead of dense updates. Gradient updates are positively skewed as most updates are near zero, so we map the 99% smallest updates (by absolute value) to zero then exchange sparse matrices. This method can be combined with quantization to further improve the compression. We explore different configurations and apply them to neural machine translation and MNIST image classification tasks. Most configurations work on MNIST, whereas different configurations reduce convergence rate on the more complex translation task. Our experiments show that we can achieve up to 49% speed up on MNIST and 22% on NMT without damaging the final accuracy or BLEU.

##### Abstract (translated by Google)
我们通过交换稀疏更新而不是密集更新来更快地分布随机梯度下降。由于大多数更新接近于零，所以渐变更新正向偏斜，所以我们将99％最小更新（通过绝对值）映射为零，然后交换稀疏矩阵。这种方法可以结合量化来进一步改善压缩。我们探索不同的配置，并将其应用于神经机器翻译和MNIST图像分类任务。大多数配置在MNIST上工作，而不同的配置在更复杂的翻译任务上降低收敛速度。我们的实验表明，在不损害最终精度或BLEU的情况下，我们可以在MNIST上达到高达49％的速度，在NMT上达到22％。

##### URL
[https://arxiv.org/abs/1704.05021](https://arxiv.org/abs/1704.05021)

##### PDF
[https://arxiv.org/pdf/1704.05021](https://arxiv.org/pdf/1704.05021)

