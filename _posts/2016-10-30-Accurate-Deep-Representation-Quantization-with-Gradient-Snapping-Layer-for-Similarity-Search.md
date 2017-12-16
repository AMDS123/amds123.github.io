---
layout: post
title: "Accurate Deep Representation Quantization with Gradient Snapping Layer for Similarity Search"
date: 2016-10-30 13:24:54
categories: arXiv_CV
tags: arXiv_CV
author: Shicong Liu, Hongtao Lu
mathjax: true
---

* content
{:toc}

##### Abstract
Recent advance of large scale similarity search involves using deeply learned representations to improve the search accuracy and use vector quantization methods to increase the search speed. However, how to learn deep representations that strongly preserve similarities between data pairs and can be accurately quantized via vector quantization remains a challenging task. Existing methods simply leverage quantization loss and similarity loss, which result in unexpectedly biased back-propagating gradients and affect the search performances. To this end, we propose a novel gradient snapping layer (GSL) to directly regularize the back-propagating gradient towards a neighboring codeword, the generated gradients are un-biased for reducing similarity loss and also propel the learned representations to be accurately quantized. Joint deep representation and vector quantization learning can be easily performed by alternatively optimize the quantization codebook and the deep neural network. The proposed framework is compatible with various existing vector quantization approaches. Experimental results demonstrate that the proposed framework is effective, flexible and outperforms the state-of-the-art large scale similarity search methods.

##### Abstract (translated by Google)
大规模相似性搜索的最新进展涉及使用深度学习的表示来提高搜索精度，并使用矢量量化方法来提高搜索速度。然而，如何学习深刻的表示，强烈保留数据对之间的相似性，并可以通过矢量量化精确量化仍然是一个具有挑战性的任务。现有的方法只是利用量化损失和相似性损失，导致意想不到的背向传播梯度，影响搜索性能。为此，我们提出了一种新的梯度捕捉层（GSL）来直接调整向相邻码字的反向传播梯度，所产生的梯度是无偏差的，以减少相似性损失，并推动学习表示被准确量化。通过交替优化量化码本和深度神经网络，可以容易地执行联合深度表示和矢量量化学习。所提出的框架与各种现有的矢量量化方法兼容。实验结果表明，所提出的框架是有效的，灵活的，胜过最先进的大规模相似性搜索方法。

##### URL
[https://arxiv.org/abs/1610.09645](https://arxiv.org/abs/1610.09645)

##### PDF
[https://arxiv.org/pdf/1610.09645](https://arxiv.org/pdf/1610.09645)

