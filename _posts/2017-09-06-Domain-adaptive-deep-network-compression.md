---
layout: post
title: "Domain-adaptive deep network compression"
date: 2017-09-06 10:26:38
categories: arXiv_CV
tags: arXiv_CV
author: Marc Masana, Joost van de Weijer, Luis Herranz, Andrew D. Bagdanov, Jose M Alvarez
mathjax: true
---

* content
{:toc}

##### Abstract
Deep Neural Networks trained on large datasets can be easily transferred to new domains with far fewer labeled examples by a process called fine-tuning. This has the advantage that representations learned in the large source domain can be exploited on smaller target domains. However, networks designed to be optimal for the source task are often prohibitively large for the target task. In this work we address the compression of networks after domain transfer. We focus on compression algorithms based on low-rank matrix decomposition. Existing methods base compression solely on learned network weights and ignore the statistics of network activations. We show that domain transfer leads to large shifts in network activations and that it is desirable to take this into account when compressing. We demonstrate that considering activation statistics when compressing weights leads to a rank-constrained regression problem with a closed-form solution. Because our method takes into account the target domain, it can more optimally remove the redundancy in the weights. Experiments show that our Domain Adaptive Low Rank (DALR) method significantly outperforms existing low-rank compression techniques. With our approach, the fc6 layer of VGG19 can be compressed more than 4x more than using truncated SVD alone -- with only a minor or no loss in accuracy. When applied to domain-transferred networks it allows for compression down to only 5-20% of the original number of parameters with only a minor drop in performance.

##### Abstract (translated by Google)
在大型数据集上训练的深度神经网络可以通过一个称为微调的过程轻松地转移到新的域中，而标记的例子却少得多。这具有以下优点：可以在较小的目标域上利用在大的源域中学习的表示。然而，设计为源任务最优的网络对于目标任务通常是过大的。在这项工作中，我们解决域转换后网络的压缩问题。我们专注于基于低秩矩阵分解的压缩算法。现有方法仅基于学习到的网络权重进行压缩，忽略网络激活的统计。我们表明，域名转移导致网络激活的巨大转变，并且在压缩时需要考虑到这一点。我们证明，考虑激活统计时压缩权重导致排序约束回归问题与封闭形式的解决方案。由于我们的方法考虑了目标域，因此可以更好地去除权重中的冗余。实验表明，我们的领域自适应低秩（DALR）方法明显优于现有的低秩压缩技术。通过我们的方法，VGG19的fc6层可以被压缩比单独使用截断SVD多4倍以上 - 只有很小或没有精度损失。当应用到域转移网络时，它只允许压缩到原始参数数量的5-20％，而性能只有很小的下降。

##### URL
[https://arxiv.org/abs/1709.01041](https://arxiv.org/abs/1709.01041)

##### PDF
[https://arxiv.org/pdf/1709.01041](https://arxiv.org/pdf/1709.01041)

