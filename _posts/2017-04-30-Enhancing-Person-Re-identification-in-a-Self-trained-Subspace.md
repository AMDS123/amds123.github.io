---
layout: post
title: "Enhancing Person Re-identification in a Self-trained Subspace"
date: 2017-04-30 00:28:52
categories: arXiv_CV
tags: arXiv_CV Re-identification Person_Re-identification Embedding Relation
author: Xun Yang, Meng Wang, Richang Hong, Qi Tian, Yong Rui
mathjax: true
---

* content
{:toc}

##### Abstract
Despite the promising progress made in recent years, person re-identification (re-ID) remains a challenging task due to the complex variations in human appearances from different camera views. For this challenging problem, a large variety of algorithms have been developed in the fully-supervised setting, requiring access to a large amount of labeled training data. However, the main bottleneck for fully-supervised re-ID is the limited availability of labeled training samples. To address this problem, in this paper, we propose a self-trained subspace learning paradigm for person re-ID which effectively utilizes both labeled and unlabeled data to learn a discriminative subspace where person images across disjoint camera views can be easily matched. The proposed approach first constructs pseudo pairwise relationships among unlabeled persons using the k-nearest neighbors algorithm. Then, with the pseudo pairwise relationships, the unlabeled samples can be easily combined with the labeled samples to learn a discriminative projection by solving an eigenvalue problem. In addition, we refine the pseudo pairwise relationships iteratively, which further improves the learning performance. A multi-kernel embedding strategy is also incorporated into the proposed approach to cope with the non-linearity in person's appearance and explore the complementation of multiple kernels. In this way, the performance of person re-ID can be greatly enhanced when training data are insufficient. Experimental results on six widely-used datasets demonstrate the effectiveness of our approach and its performance can be comparable to the reported results of most state-of-the-art fully-supervised methods while using much fewer labeled data.

##### Abstract (translated by Google)
尽管近年来取得了令人鼓舞的进展，但由于不同摄像机视图的人脸形状复杂，人重新识别（重新识别）仍然是一项具有挑战性的任务。对于这个具有挑战性的问题，在完全监督的设置中已经开发了各种各样的算法，需要访问大量标记的训练数据。然而，完全监督的重新识别的主要瓶颈是有标签的训练样本的有限可用性。为了解决这个问题，本文提出了一种自我训练的人员重认识子空间学习范式，它有效地利用了标记和未标记的数据来学习一个判别子空间，在这个子空间中，不相交的摄像机视图上的人物图像可以很容易地匹配。所提出的方法首先使用k最近邻算法构造未标记人员之间的伪成对关系。然后，利用伪成对关系，可以将未标记的样本容易地与标记的样本组合以通过求解特征值问题来学习有区别的投影。此外，我们迭代地改进了伪成对关系，进一步提高了学习效果。提出的多核嵌入策略也被应用于处理人脸外观的非线性问题，探索多核互补问题。这样，当训练数据不足时，可以大大提高人员再认证的性能。在六个广泛使用的数据集上的实验结果证明了我们的方法的有效性，其性能可以与大多数最先进的全监督方法的报告结果相比较，同时使用少得多的标记数据。

##### URL
[https://arxiv.org/abs/1704.06020](https://arxiv.org/abs/1704.06020)

##### PDF
[https://arxiv.org/pdf/1704.06020](https://arxiv.org/pdf/1704.06020)

