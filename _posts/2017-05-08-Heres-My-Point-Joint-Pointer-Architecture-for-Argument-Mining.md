---
layout: post
title: "Here's My Point: Joint Pointer Architecture for Argument Mining"
date: 2017-05-08 21:59:03
categories: arXiv_CL
tags: arXiv_CL Relation
author: Peter Potash, Alexey Romanov, Anna Rumshisky
mathjax: true
---

* content
{:toc}

##### Abstract
One of the major goals in automated argumentation mining is to uncover the argument structure present in argumentative text. In order to determine this structure, one must understand how different individual components of the overall argument are linked. General consensus in this field dictates that the argument components form a hierarchy of persuasion, which manifests itself in a tree structure. This work provides the first neural network-based approach to argumentation mining, focusing on the two tasks of extracting links between argument components, and classifying types of argument components. In order to solve this problem, we propose to use a joint model that is based on a Pointer Network architecture. A Pointer Network is appealing for this task for the following reasons: 1) It takes into account the sequential nature of argument components; 2) By construction, it enforces certain properties of the tree structure present in argument relations; 3) The hidden representations can be applied to auxiliary tasks. In order to extend the contribution of the original Pointer Network model, we construct a joint model that simultaneously attempts to learn the type of argument component, as well as continuing to predict links between argument components. The proposed joint model achieves state-of-the-art results on two separate evaluation corpora, achieving far superior performance than a regular Pointer Network model. Our results show that optimizing for both tasks, and adding a fully-connected layer prior to recurrent neural network input, is crucial for high performance.

##### Abstract (translated by Google)
自动论证挖掘的主要目标之一就是揭示议论文中存在的论证结构。为了确定这个结构，我们必须了解整个论证的不同组成部分是如何联系在一起的。在这个领域的普遍共识表明，论证的组成部分形成了一个说服的层次，它表现为一个树型结构。这项工作提供了第一个基于神经网络的论证挖掘方法，重点是提取参数组件之间的链接和分类参数组件类型的两个任务。为了解决这个问题，我们建议使用基于指针网络结构的联合模型。指针网络对于这个任务有吸引力，理由如下：1）它考虑了参数组件的顺序性; 2）通过构建，强化论证关系中存在的树结构的某些性质; 3）隐藏表示可以应用于辅助任务。为了扩大原始指针网络模型的贡献，我们构造了一个联合模型，同时尝试学习变元的类型，并继续预测变元之间的联系。所提出的联合模型在两个单独的评估语料库上实现了最新的结果，实现了比常规的指针网络模型更优越的性能。我们的研究结果表明，优化这两个任务，并在循环神经网络输入之前添加一个完全连接的层对高性能至关重要。

##### URL
[https://arxiv.org/abs/1612.08994](https://arxiv.org/abs/1612.08994)

##### PDF
[https://arxiv.org/pdf/1612.08994](https://arxiv.org/pdf/1612.08994)

