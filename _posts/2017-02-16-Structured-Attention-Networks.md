---
layout: post
title: "Structured Attention Networks"
date: 2017-02-16 17:52:03
categories: arXiv_SD
tags: arXiv_SD Segmentation Attention Embedding Inference
author: Yoon Kim, Carl Denton, Luong Hoang, Alexander M. Rush
mathjax: true
---

* content
{:toc}

##### Abstract
Attention networks have proven to be an effective approach for embedding categorical inference within a deep neural network. However, for many tasks we may want to model richer structural dependencies without abandoning end-to-end training. In this work, we experiment with incorporating richer structural distributions, encoded using graphical models, within deep networks. We show that these structured attention networks are simple extensions of the basic attention procedure, and that they allow for extending attention beyond the standard soft-selection approach, such as attending to partial segmentations or to subtrees. We experiment with two different classes of structured attention networks: a linear-chain conditional random field and a graph-based parsing model, and describe how these models can be practically implemented as neural network layers. Experiments show that this approach is effective for incorporating structural biases, and structured attention networks outperform baseline attention models on a variety of synthetic and real tasks: tree transduction, neural machine translation, question answering, and natural language inference. We further find that models trained in this way learn interesting unsupervised hidden representations that generalize simple attention.

##### Abstract (translated by Google)
注意网络已经被证明是一种在深度神经网络中嵌入分类推理的有效方法。但是，对于许多任务，我们可能希望建立更丰富的结构依赖关系，而不会放弃端到端的培训。在这项工作中，我们尝试在深度网络中结合使用图形模型编码的更丰富的结构分布。我们表明，这些结构化的关注网络是基本关注程序的简单扩展，并且它们允许将注意力扩展到标准的软选择方法之外，例如参与部分分割或子树。我们尝试了两种不同的结构化关注网络类型：一个线性链条件随机场和一个基于图的解析模型，并描述这些模型如何实际地作为神经网络层实现。实验表明，这种方法是有效的纳入结构偏见，结构化的关注网络胜过基准关注模型的各种合成和实际任务：树转导，神经机器翻译，问题回答和自然语言推理。我们进一步发现，以这种方式训练的模型学习有趣的无监督隐藏的表示，推广简单的关注。

##### URL
[https://arxiv.org/abs/1702.00887](https://arxiv.org/abs/1702.00887)

##### PDF
[https://arxiv.org/pdf/1702.00887](https://arxiv.org/pdf/1702.00887)

