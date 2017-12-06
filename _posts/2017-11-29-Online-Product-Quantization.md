---
layout: post
title: "Online Product Quantization"
date: 2017-11-29 11:17:04
categories: arXiv_CV
tags: arXiv_CV
author: Donna Xu, Ivor W. Tsang, Ying Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Approximate nearest neighbor (ANN) search has achieved great success in many tasks. However, existing popular methods for ANN search, such as hashing and quantization methods, are designed for static databases only. They cannot handle well the database with data distribution evolving dynamically, due to the high computational effort for retraining the model based on the new database. In this paper, we address the problem by developing an online product quantization (online PQ) model and incrementally updating the quantization codebook that accommodates to the incoming streaming data. Moreover, to further alleviate the issue of large scale computation for the online PQ update, we design two budget constraints for the model to update partial PQ codebook instead of all. We derive a loss bound which guarantees the performance of our online PQ model. Furthermore, we develop an online PQ model over a sliding window with both data insertion and deletion supported, to reflect the real-time behaviour of the data. The experiments demonstrate that our online PQ model is both time-efficient and effective for ANN search in dynamic large scale databases compared with baseline methods and the idea of partial PQ codebook update further reduces the update cost.

##### Abstract (translated by Google)
近似最近邻（ANN）搜索在许多任务中取得了巨大的成功。然而，目前流行的神经网络搜索方法，如哈希和量化方法，只能用于静态数据库。由于基于新数据库对模型进行再训练的计算量很大，因此他们不能很好地处理数据分布动态变化的数据库。在本文中，我们通过开发在线产品量化（在线PQ）模型并递增地更新适应传入流数据的量化码本来解决该问题。此外，为了进一步缓解在线PQ更新的大规模计算问题，我们设计了两个预算约束模型来更新部分PQ码本而不是全部。我们推导出损失界限，保证我们的在线PQ模型的性能。此外，我们开发了滑动窗口上的在线PQ模型，同时支持数据插入和删除，以反映数据的实时行为。实验结果表明，与基线方法相比，我们的在线PQ模型在动态大规模数据库的ANN搜索中既省时又有效，部分PQ码本更新的思想进一步降低了更新代价。

##### URL
[https://arxiv.org/abs/1711.10775](https://arxiv.org/abs/1711.10775)

