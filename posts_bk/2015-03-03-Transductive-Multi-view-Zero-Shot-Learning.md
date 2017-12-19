---
layout: post
title: "Transductive Multi-view Zero-Shot Learning"
date: 2015-03-03 04:43:44
categories: arXiv_CV
tags: arXiv_CV Embedding Transfer_Learning Recognition
author: Yanwei Fu, Timothy M. Hospedales, Tao Xiang, Shaogang Gong
mathjax: true
---

* content
{:toc}

##### Abstract
Most existing zero-shot learning approaches exploit transfer learning via an intermediate-level semantic representation shared between an annotated auxiliary dataset and a target dataset with different classes and no annotation. A projection from a low-level feature space to the semantic representation space is learned from the auxiliary dataset and is applied without adaptation to the target dataset. In this paper we identify two inherent limitations with these approaches. First, due to having disjoint and potentially unrelated classes, the projection functions learned from the auxiliary dataset/domain are biased when applied directly to the target dataset/domain. We call this problem the projection domain shift problem and propose a novel framework, transductive multi-view embedding, to solve it. The second limitation is the prototype sparsity problem which refers to the fact that for each target class, only a single prototype is available for zero-shot learning given a semantic representation. To overcome this problem, a novel heterogeneous multi-view hypergraph label propagation method is formulated for zero-shot learning in the transductive embedding space. It effectively exploits the complementary information offered by different semantic representations and takes advantage of the manifold structures of multiple representation spaces in a coherent manner. We demonstrate through extensive experiments that the proposed approach (1) rectifies the projection shift between the auxiliary and target domains, (2) exploits the complementarity of multiple semantic representations, (3) significantly outperforms existing methods for both zero-shot and N-shot recognition on three image and video benchmark datasets, and (4) enables novel cross-view annotation tasks.

##### Abstract (translated by Google)
大多数现有的零点学习方法利用转移学习，通过注释的辅助数据集和具有不同类的目标数据集之间共享的中间级别语义表示来进行转移学习，并且没有注释。从辅助数据集中学习从低级特征空间到语义表示空间的投影，并且在不适应目标数据集的情况下被应用。在本文中，我们确定了这些方法的两个固有限制。首先，由于具有不相关的和可能不相关的类，直接应用到目标数据集/域时，从辅助数据集/域学习的投影函数是有偏见的。我们把这个问题称为投影域转移问题，并提出一个新的框架，即多视角嵌入，来解决它。第二个限制是原型稀疏性问题，它指的是对于每个目标类，只有一个原型可用于给定语义表示的零点学习。针对这一问题，提出了一种新颖的异构多视图超图标签传播方法，用于传导嵌入空间的零点学习。它有效地利用了不同语义表示所提供的互补信息，并以一致的方式利用了多个表示空间的流形结构。我们通过大量的实验证明，所提出的方法（1）纠正了辅助域和目标域之间的投影转换，（2）利用了多个语义表示的互补性，（3）零射击和N射击明显优于现有方法对三个图像和视频基准数据集的识别，以及（4）使得新颖的交叉视图注释任务成为可能。

##### URL
[https://arxiv.org/abs/1501.04560](https://arxiv.org/abs/1501.04560)

##### PDF
[https://arxiv.org/pdf/1501.04560](https://arxiv.org/pdf/1501.04560)

