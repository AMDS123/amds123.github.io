---
layout: post
title: "Associative Domain Adaptation"
date: 2017-08-02 21:38:45
categories: arXiv_CV
tags: arXiv_CV Embedding CNN Classification
author: Philip Haeusser, Thomas Frerix, Alexander Mordvintsev, Daniel Cremers
mathjax: true
---

* content
{:toc}

##### Abstract
We propose associative domain adaptation, a novel technique for end-to-end domain adaptation with neural networks, the task of inferring class labels for an unlabeled target domain based on the statistical properties of a labeled source domain. Our training scheme follows the paradigm that in order to effectively derive class labels for the target domain, a network should produce statistically domain invariant embeddings, while minimizing the classification error on the labeled source domain. We accomplish this by reinforcing associations between source and target data directly in embedding space. Our method can easily be added to any existing classification network with no structural and almost no computational overhead. We demonstrate the effectiveness of our approach on various benchmarks and achieve state-of-the-art results across the board with a generic convolutional neural network architecture not specifically tuned to the respective tasks. Finally, we show that the proposed association loss produces embeddings that are more effective for domain adaptation compared to methods employing maximum mean discrepancy as a similarity measure in embedding space.

##### Abstract (translated by Google)
我们提出联想域自适应，一种新的端到端的神经网络域自适应技术，基于标记的源域的统计特性来推断未标记目标域的类别标签。我们的训练方案遵循的范例是，为了有效地导出目标域的类标签，网络应该产生统计域不变嵌入，同时最小化标记源域上的分类错误。我们通过直接在嵌入空间中加强源数据与目标数据之间的关联来实现这一点。我们的方法可以很容易地添加到任何现有的分类网络，没有结构，几乎没有计算开销。我们证明了我们的方法在各种基准测试中的有效性，并且通过一个通用的卷积神经网络架构来全面实现最新的结果。最后，我们表明，与使用最大均值差异作为嵌入空间中的相似性度量的方法相比，所提出的关联损失产生了对域适应更有效的嵌入。

##### URL
[https://arxiv.org/abs/1708.00938](https://arxiv.org/abs/1708.00938)

##### PDF
[https://arxiv.org/pdf/1708.00938](https://arxiv.org/pdf/1708.00938)

