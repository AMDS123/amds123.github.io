---
layout: post
title: "Hard Mixtures of Experts for Large Scale Weakly Supervised Vision"
date: 2017-04-20 23:45:27
categories: arXiv_CV
tags: arXiv_CV Weakly_Supervised Embedding CNN Prediction Gradient_Descent
author: Sam Gross, Marc'Aurelio Ranzato, Arthur Szlam
mathjax: true
---

* content
{:toc}

##### Abstract
Training convolutional networks (CNN's) that fit on a single GPU with minibatch stochastic gradient descent has become effective in practice. However, there is still no effective method for training large CNN's that do not fit in the memory of a few GPU cards, or for parallelizing CNN training. In this work we show that a simple hard mixture of experts model can be efficiently trained to good effect on large scale hashtag (multilabel) prediction tasks. Mixture of experts models are not new (Jacobs et. al. 1991, Collobert et. al. 2003), but in the past, researchers have had to devise sophisticated methods to deal with data fragmentation. We show empirically that modern weakly supervised data sets are large enough to support naive partitioning schemes where each data point is assigned to a single expert. Because the experts are independent, training them in parallel is easy, and evaluation is cheap for the size of the model. Furthermore, we show that we can use a single decoding layer for all the experts, allowing a unified feature embedding space. We demonstrate that it is feasible (and in fact relatively painless) to train far larger models than could be practically trained with standard CNN architectures, and that the extra capacity can be well used on current datasets.

##### Abstract (translated by Google)
使用minibatch随机梯度下降法来适应单GPU的卷积网络（CNN）已经在实践中变得有效。然而，目前还没有一种有效的方法来训练大型的CNN，它们不适合于一些GPU卡的存储，也不适合CNN训练的并行化。在这项工作中，我们表明，一个简单的混合专家模型可以有效地训练，以大规模的标签（多标签）预测任务效果良好。专家模型的混合并不是新的（Jacobs等，1991，Collobert等，2003），但过去，研究人员必须设计复杂的方法来处理数据碎片。我们经验地显示，现代弱监督的数据集足够大，以支持每个数据点被分配给单个专家的朴素分区方案。由于专家是独立的，所以对他们进行并行训练是很容易的，对于模型的大小来说，评估是很便宜的。此外，我们显示我们可以为所有专家使用单个解码层，从而允许统一的功能嵌入空间。我们证明，训练比可以用标准CNN架构实际训练的更大的模型是可行的（并且实际上是相对无痛的），并且额外容量可以很好地用于当前数据集。

##### URL
[https://arxiv.org/abs/1704.06363](https://arxiv.org/abs/1704.06363)

##### PDF
[https://arxiv.org/pdf/1704.06363](https://arxiv.org/pdf/1704.06363)

