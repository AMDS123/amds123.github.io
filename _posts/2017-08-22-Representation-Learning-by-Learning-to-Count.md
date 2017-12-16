---
layout: post
title: "Representation Learning by Learning to Count"
date: 2017-08-22 17:33:47
categories: arXiv_CV
tags: arXiv_CV Transfer_Learning Represenation_Learning Relation
author: Mehdi Noroozi, Hamed Pirsiavash, Paolo Favaro
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a novel method for representation learning that uses an artificial supervision signal based on counting visual primitives. This supervision signal is obtained from an equivariance relation, which does not require any manual annotation. We relate transformations of images to transformations of the representations. More specifically, we look for the representation that satisfies such relation rather than the transformations that match a given representation. In this paper, we use two image transformations in the context of counting: scaling and tiling. The first transformation exploits the fact that the number of visual primitives should be invariant to scale. The second transformation allows us to equate the total number of visual primitives in each tile to that in the whole image. These two transformations are combined in one constraint and used to train a neural network with a contrastive loss. The proposed task produces representations that perform on par or exceed the state of the art in transfer learning benchmarks.

##### Abstract (translated by Google)
我们引入了一种新颖的表示学习方法，它使用基于计数视觉原语的人工监督信号。这个监督信号是从等变量关系得到的，不需要任何手工注释。我们将图像的变换与表示的变换联系起来。更具体地说，我们寻找满足这种关系的表示，而不是匹配给定表示的转换。在本文中，我们在计数的上下文中使用两个图像转换：缩放和平铺。第一种转换利用了视觉基元的数量应该不变的规模。第二个转换允许我们将每个拼贴块中的视觉基元的总数等同于整个图像中的视觉基元的总数。这两个转换被合并在一个约束中，用来训练具有对比损失的神经网络。建议的任务产生的表现，表现等于或超过转移学习基准的艺术水平。

##### URL
[https://arxiv.org/abs/1708.06734](https://arxiv.org/abs/1708.06734)

##### PDF
[https://arxiv.org/pdf/1708.06734](https://arxiv.org/pdf/1708.06734)

