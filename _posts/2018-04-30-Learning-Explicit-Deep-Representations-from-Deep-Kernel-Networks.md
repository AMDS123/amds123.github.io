---
layout: post
title: "Learning Explicit Deep Representations from Deep Kernel Networks"
date: 2018-04-30 12:42:02
categories: arXiv_CV
tags: arXiv_CV
author: Mingyuan Jiu, Hichem Sahbi
mathjax: true
---

* content
{:toc}

##### Abstract
Deep kernel learning aims at designing nonlinear combinations of multiple standard elementary kernels by training deep networks. This scheme has proven to be effective, but intractable when handling large-scale datasets especially when the depth of the trained networks increases; indeed, the complexity of evaluating these networks scales quadratically w.r.t. the size of training data and linearly w.r.t. the depth of the trained networks. In this paper, we address the issue of efficient computation in Deep Kernel Networks (DKNs) by designing effective maps in the underlying Reproducing Kernel Hilbert Spaces. Given a pretrained DKN, our method builds its associated Deep Map Network (DMN) whose inner product approximates the original network while being far more efficient. The design principle of our method is greedy and achieved layer-wise, by finding maps that approximate DKNs at different (input, intermediate and output) layers. This design also considers an extra fine-tuning step based on unsupervised learning, that further enhances the generalization ability of the trained DMNs. When plugged into SVMs, these DMNs turn out to be as accurate as the underlying DKNs while being at least an order of magnitude faster on large-scale datasets, as shown through extensive experiments on the challenging ImageCLEF and COREL5k benchmarks.

##### Abstract (translated by Google)
深度内核学习旨在通过训练深度网络来设计多个标准基本内核的非线性组合。该方案已被证明是有效的，但在处理大规模数据集时尤为棘手，特别是当训练网络的深度增加时;事实上，评估这些网络的复杂性可以按照二次方来衡量。训练数据的大小和线性w.r.t.训练有素的网络的深度。在本文中，我们通过在底层复制核Hilbert空间中设计有效映射来解决深层核心网络（DKN）中高效计算的问题。鉴于预训DKN，我们的方法建立了其相关的深层地图网络（DMN），其内部产品接近原始网络，同时效率更高。我们的方法的设计原理是贪婪的，并通过找到在不同（输入层，中间层和输出层）处接近DKN的映射来实现分层。该设计还考虑基于无监督学习的额外微调步骤，其进一步增强了训练的DMN的泛化能力。当插入SVM时，这些DMN的结果与底层DKNs一样精确，而在大规模数据集上至少快一个数量级，如通过对具有挑战性的ImageCLEF和COREL5k基准的大量实验所显示的。

##### URL
[https://arxiv.org/abs/1804.11159](https://arxiv.org/abs/1804.11159)

##### PDF
[https://arxiv.org/pdf/1804.11159](https://arxiv.org/pdf/1804.11159)

