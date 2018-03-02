---
layout: post
title: "Learning Longer-term Dependencies in RNNs with Auxiliary Losses"
date: 2018-03-01 00:28:07
categories: arXiv_AI
tags: arXiv_AI Regularization Image_Classification Optimization RNN Classification
author: Trieu H. Trinh, Andrew M. Dai, Thang Luong, Quoc V. Le
mathjax: true
---

* content
{:toc}

##### Abstract
Despite recent advances in training recurrent neural networks (RNNs), capturing long-term dependencies in sequences remains a fundamental challenge. Most approaches use backpropagation through time (BPTT), which is difficult to scale to very long sequences. This paper proposes a simple method that improves the ability to capture long term dependencies in RNNs by adding an unsupervised auxiliary loss to the original objective. This auxiliary loss forces RNNs to either reconstruct previous events or predict next events in a sequence, making truncated backpropagation feasible for long sequences and also improving full BPTT. We evaluate our method on a variety of settings, including pixel-by-pixel image classification with sequence lengths up to 16\,000, and a real document classification benchmark. Our results highlight good performance and resource efficiency of this approach over competitive baselines, including other recurrent models and a comparable sized Transformer. Further analyses reveal beneficial effects of the auxiliary loss on optimization and regularization, as well as extreme cases where there is little to no backpropagation.

##### Abstract (translated by Google)
尽管最近在训练递归神经网络（RNN）方面取得了进展，但捕获序列中的长期依赖仍然是一个基本挑战。大多数方法使用反向传播时间（BPTT），这很难调整到很长的序列。本文提出了一种简单的方法，通过向原始目标添加无监督辅助损失来提高捕获RNN中长期相关性的能力。这种辅助损失迫使RNN重建先前的事件或预测序列中的下一个事件，使得截断后向传播对于长序列是可行的，并且还改善了完整的BPTT。我们在多种设置中评估我们的方法，包括序列长度高达16,000的逐像素图像分类和真实文档分类基准。我们的研究结果突出了这种方法在竞争基线方面的良好性能和资源效率，其中包括其他经常性模型和可比尺寸的变压器。进一步的分析揭示了辅助损失对优化和正则化的有益影响，以及几乎没有反向传播的极端情况。

##### URL
[http://arxiv.org/abs/1803.00144](http://arxiv.org/abs/1803.00144)

##### PDF
[http://arxiv.org/pdf/1803.00144](http://arxiv.org/pdf/1803.00144)

