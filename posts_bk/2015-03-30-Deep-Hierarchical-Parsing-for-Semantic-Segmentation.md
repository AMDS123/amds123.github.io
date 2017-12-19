---
layout: post
title: "Deep Hierarchical Parsing for Semantic Segmentation"
date: 2015-03-30 20:03:01
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Classification
author: Abhishek Sharma, Oncel Tuzel, David W. Jacobs
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a learning-based approach to scene parsing inspired by the deep Recursive Context Propagation Network (RCPN). RCPN is a deep feed-forward neural network that utilizes the contextual information from the entire image, through bottom-up followed by top-down context propagation via random binary parse trees. This improves the feature representation of every super-pixel in the image for better classification into semantic categories. We analyze RCPN and propose two novel contributions to further improve the model. We first analyze the learning of RCPN parameters and discover the presence of bypass error paths in the computation graph of RCPN that can hinder contextual propagation. We propose to tackle this problem by including the classification loss of the internal nodes of the random parse trees in the original RCPN loss function. Secondly, we use an MRF on the parse tree nodes to model the hierarchical dependency present in the output. Both modifications provide performance boosts over the original RCPN and the new system achieves state-of-the-art performance on Stanford Background, SIFT-Flow and Daimler urban datasets.

##### Abstract (translated by Google)
本文提出了一种基于学习的场景分析方法，受深度递归上下文传播网络（RCPN）的启发。 RCPN是一个深度前馈神经网络，利用整个图像的上下文信息，通过自下而上的方式，然后通过随机二进制解析树自上而下的上下文传播。这改善了图像中每个超像素的特征表示，以便更好地分类为语义类别。我们分析RCPN并提出两个新的贡献来进一步改进模型。我们首先分析RCPN参数的学习，发现RCPN计算图中旁路错误路径的存在可能阻碍上下文传播。我们建议通过在原始RCPN丢失函数中包含随机分析树的内部节点的分类损失来解决这个问题。其次，我们在分析树节点上使用MRF来模拟输出中存在的层次依赖关系。这两种修改都提高了原始RCPN的性能，新系统在斯坦福背景，SIFT-Flow和戴姆勒城市数据集上实现了最先进的性能。

##### URL
[https://arxiv.org/abs/1503.02725](https://arxiv.org/abs/1503.02725)

##### PDF
[https://arxiv.org/pdf/1503.02725](https://arxiv.org/pdf/1503.02725)

