---
layout: post
title: "Unsupervised Cross-Domain Recognition by Identifying Compact Joint Subspaces"
date: 2015-09-05 17:12:21
categories: arXiv_CV
tags: arXiv_CV Sentiment Sentiment_Classification Classification Recognition
author: Yuewei Lin, Jing Chen, Yu Cao, Youjie Zhou, Lingfeng Zhang, Yuan Yan Tang, Song Wang
mathjax: true
---

* content
{:toc}

##### Abstract
This paper introduces a new method to solve the cross-domain recognition problem. Different from the traditional domain adaption methods which rely on a global domain shift for all classes between source and target domain, the proposed method is more flexible to capture individual class variations across domains. By adopting a natural and widely used assumption -- "the data samples from the same class should lay on a low-dimensional subspace, even if they come from different domains", the proposed method circumvents the limitation of the global domain shift, and solves the cross-domain recognition by finding the compact joint subspaces of source and target domain. Specifically, given labeled samples in source domain, we construct subspaces for each of the classes. Then we construct subspaces in the target domain, called anchor subspaces, by collecting unlabeled samples that are close to each other and highly likely all fall into the same class. The corresponding class label is then assigned by minimizing a cost function which reflects the overlap and topological structure consistency between subspaces across source and target domains, and within anchor subspaces, respectively.We further combine the anchor subspaces to corresponding source subspaces to construct the compact joint subspaces. Subsequently, one-vs-rest SVM classifiers are trained in the compact joint subspaces and applied to unlabeled data in the target domain. We evaluate the proposed method on two widely used datasets: object recognition dataset for computer vision tasks, and sentiment classification dataset for natural language processing tasks. Comparison results demonstrate that the proposed method outperforms the comparison methods on both datasets.

##### Abstract (translated by Google)
本文介绍了一种解决跨域识别问题的新方法。与源域和目标域之间所有类别依赖全局域名转移的传统域名自适应方法不同，所提出的方法能够更加灵活地捕获跨域的个体类别变体。通过采用一个自然的，被广泛使用的假设 - 即“来自同一类的数据样本应该位于一个低维子空间，即使它们来自不同的领域”，该方法避开了全局域转移的局限性，解决了通过查找源域和目标域的紧凑联合子空间来进行跨域识别。具体来说，给定源域标签样本，我们为每个类构造子空间。然后我们通过收集相互靠近的非标签样本，很有可能属于同一个类，在目标域中构造称为锚子空间的子空间。然后通过最小化代价函数来分配相应的类别标签，所述代价函数分别反映源域和目标域之间以及锚子空间内的子空间之间的重叠和拓扑结构一致性。我们进一步将锚子空间组合到相应的子子空间以构建紧密联合子空间。随后，在紧凑联合子空间中训练单SVVM分类器，并将其应用于目标域中的未标记数据。我们在两个广泛使用的数据集上评估所提出的方法：用于计算机视觉任务的对象识别数据集和用于自然语言处理任务的情感分类数据集。比较结果表明，所提出的方法优于两个数据集上的比较方法。

##### URL
[https://arxiv.org/abs/1509.01719](https://arxiv.org/abs/1509.01719)

##### PDF
[https://arxiv.org/pdf/1509.01719](https://arxiv.org/pdf/1509.01719)

