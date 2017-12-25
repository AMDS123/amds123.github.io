---
layout: post
title: "Recurrent Pixel Embedding for Instance Grouping"
date: 2017-12-22 01:48:53
categories: arXiv_CV
tags: arXiv_CV Segmentation Embedding Semantic_Segmentation Classification Detection
author: Shu Kong, Charless Fowlkes
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a differentiable, end-to-end trainable framework for solving pixel-level grouping problems such as instance segmentation consisting of two novel components. First, we regress pixels into a hyper-spherical embedding space so that pixels from the same group have high cosine similarity while those from different groups have similarity below a specified margin. We analyze the choice of embedding dimension and margin, relating them to theoretical results on the problem of distributing points uniformly on the sphere. Second, to group instances, we utilize a variant of mean-shift clustering, implemented as a recurrent neural network parameterized by kernel bandwidth. This recurrent grouping module is differentiable, enjoys convergent dynamics and probabilistic interpretability. Backpropagating the group-weighted loss through this module allows learning to focus on only correcting embedding errors that won't be resolved during subsequent clustering. Our framework, while conceptually simple and theoretically abundant, is also practically effective and computationally efficient. We demonstrate substantial improvements over state-of-the-art instance segmentation for object proposal generation, as well as demonstrating the benefits of grouping loss for classification tasks such as boundary detection and semantic segmentation.

##### Abstract (translated by Google)
我们引入了一个可区分的，端到端的可训练框架来解决像素级分组问题，例如由两个新颖组件组成的实例分割。首先，我们将像素回归到一个超球形的嵌入空间，使得来自同一组的像素具有较高的余弦相似性，而来自不同组的像素具有低于指定的边缘的相似性。我们分析嵌入维数和边界的选择，将它们与关于均匀分布在球体上的问题的理论结果相关联。其次，为了对实例进行分组，我们利用均值漂移聚类的变体，实现为由内核带宽参数化的递归神经网络。这种反复分组模块是可微的，具有趋同动态性和概率可解性。通过这个模块反向传播群加权损失使得学习的重点仅仅是纠正在随后的聚类中不会被解决的嵌入错误。我们的框架虽然在概念上简单而且理论上丰富，但实际上也是有效的，并且计算效率高。我们展示了对象建议生成中最先进的实例分割的实质性改进，以及展示了分类任务（如边界检测和语义分割）的分组损失的好处。

##### URL
[https://arxiv.org/abs/1712.08273](https://arxiv.org/abs/1712.08273)

##### PDF
[https://arxiv.org/pdf/1712.08273](https://arxiv.org/pdf/1712.08273)

