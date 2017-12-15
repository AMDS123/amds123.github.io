---
layout: post
title: "Beyond Sharing Weights for Deep Domain Adaptation"
date: 2016-11-17 13:51:31
categories: arXiv_CV
tags: arXiv_CV Sparse Detection Recognition
author: Artem Rozantsev, Mathieu Salzmann, Pascal Fua
mathjax: true
---

* content
{:toc}

##### Abstract
The performance of a classifier trained on data coming from a specific domain typically degrades when applied to a related but different one. While annotating many samples from the new domain would address this issue, it is often too expensive or impractical. Domain Adaptation has therefore emerged as a solution to this problem; It leverages annotated data from a source domain, in which it is abundant, to train a classifier to operate in a target domain, in which it is either sparse or even lacking altogether. In this context, the recent trend consists of learning deep architectures whose weights are shared for both domains, which essentially amounts to learning domain invariant features. Here, we show that it is more effective to explicitly model the shift from one domain to the other. To this end, we introduce a two-stream architecture, where one operates in the source domain and the other in the target domain. In contrast to other approaches, the weights in corresponding layers are related but not shared. We demonstrate that this both yields higher accuracy than state-of-the-art methods on several object recognition and detection tasks and consistently outperforms networks with shared weights in both supervised and unsupervised settings.

##### Abstract (translated by Google)
对来自特定领域的数据进行训练的分类器的性能通常在应用于相关但不同的领域时降级。虽然注释来自新域的许多样本将解决这个问题，但是这通常太昂贵或不切实际。因此，域适应已成为解决这个问题的方法。它利用来自源域的带注释的数据，在这个源域中存在大量的训练分类器以在目标域中操作，其中该目标域或者是稀疏的，或者甚至是完全没有的。在这种情况下，最近的趋势包括学习深层架构，其权重为两个领域共享，基本上相当于学习领域不变特征。在这里，我们表明，明确建模从一个域到另一个域的转换更为有效。为此，我们引入一个双流体系结构，其中一个在源域中运行，另一个在目标域中运行。与其他方法相比，相应层中的权重是相关的，但不共享。我们证明，这两个产生更高的准确性比最先进的方法在几个对象的识别和检测任务，并始终优于在监督和非监督设置共享权重的网络。

##### URL
[https://arxiv.org/abs/1603.06432](https://arxiv.org/abs/1603.06432)

##### PDF
[https://arxiv.org/pdf/1603.06432](https://arxiv.org/pdf/1603.06432)

