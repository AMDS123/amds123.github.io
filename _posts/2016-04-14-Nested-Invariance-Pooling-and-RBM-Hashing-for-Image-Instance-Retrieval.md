---
layout: post
title: "Nested Invariance Pooling and RBM Hashing for Image Instance Retrieval"
date: 2016-04-14 14:11:18
categories: arXiv_CV
tags: arXiv_CV Regularization CNN
author: Olivier Morère, Jie Lin, Antoine Veillard, Vijay Chandrasekhar, Tomaso Poggio
mathjax: true
---

* content
{:toc}

##### Abstract
The goal of this work is the computation of very compact binary hashes for image instance retrieval. Our approach has two novel contributions. The first one is Nested Invariance Pooling (NIP), a method inspired from i-theory, a mathematical theory for computing group invariant transformations with feed-forward neural networks. NIP is able to produce compact and well-performing descriptors with visual representations extracted from convolutional neural networks. We specifically incorporate scale, translation and rotation invariances but the scheme can be extended to any arbitrary sets of transformations. We also show that using moments of increasing order throughout nesting is important. The NIP descriptors are then hashed to the target code size (32-256 bits) with a Restricted Boltzmann Machine with a novel batch-level regularization scheme specifically designed for the purpose of hashing (RBMH). A thorough empirical evaluation with state-of-the-art shows that the results obtained both with the NIP descriptors and the NIP+RBMH hashes are consistently outstanding across a wide range of datasets.

##### Abstract (translated by Google)
这项工作的目标是计算非常紧凑的二进制散列图像实例检索。我们的方法有两个新颖的贡献。第一个是嵌套不变池（NIP），一种从i-理论启发的方法，一种用前馈神经网络计算群不变转换的数学理论。 NIP能够从卷积神经网络中提取具有可视表示的紧凑且性能良好的描述符。我们具体地结合了规模，平移和旋转不变性，但是这个方案可以扩展到任意的变换集合。我们还表明，在整个嵌套中使用递增顺序的时刻是重要的。然后用限制玻尔兹曼机（Boltzmann Machine）将NIP描述符散列到目标代码大小（32-256位），该机采用专门为散列（RBMH）设计的新型批量级正则化方案。通过最先进的经验评估表明，在NIP描述符和NIP + RBMH哈希中获得的结果在广泛的数据集中始终如一。

##### URL
[https://arxiv.org/abs/1603.04595](https://arxiv.org/abs/1603.04595)

##### PDF
[https://arxiv.org/pdf/1603.04595](https://arxiv.org/pdf/1603.04595)

