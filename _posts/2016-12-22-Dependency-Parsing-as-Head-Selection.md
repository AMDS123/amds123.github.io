---
layout: post
title: "Dependency Parsing as Head Selection"
date: 2016-12-22 15:28:34
categories: arXiv_CL
tags: arXiv_CL Inference
author: Xingxing Zhang, Jianpeng Cheng, Mirella Lapata
mathjax: true
---

* content
{:toc}

##### Abstract
Conventional graph-based dependency parsers guarantee a tree structure both during training and inference. Instead, we formalize dependency parsing as the problem of independently selecting the head of each word in a sentence. Our model which we call \textsc{DeNSe} (as shorthand for {\bf De}pendency {\bf N}eural {\bf Se}lection) produces a distribution over possible heads for each word using features obtained from a bidirectional recurrent neural network. Without enforcing structural constraints during training, \textsc{DeNSe} generates (at inference time) trees for the overwhelming majority of sentences, while non-tree outputs can be adjusted with a maximum spanning tree algorithm. We evaluate \textsc{DeNSe} on four languages (English, Chinese, Czech, and German) with varying degrees of non-projectivity. Despite the simplicity of the approach, our parsers are on par with the state of the art.

##### Abstract (translated by Google)
传统的基于图形的依赖分析器在训练和推理期间保证树结构。相反，我们把依赖分析形式化为独立选择句子中每个单词头部的问题。我们称之为\ textsc {DeNSe}的模型（作为{\ bf De} pendency {\ bf N} eural {\ bf Section}的简写）为每个单词使用从双向递归神经网络。在训练过程中，如果不加强结构约束，\ textsc {DeNSe}为绝大多数句子生成（在推理时）树，而非树输出可以用最大生成树算法进行调整。我们用四种语言（英文，中文，捷克文和德文）评估\ textsc {DeNSe}，并且具有不同程度的非投射性。尽管这种方法很简单，但我们的解析器与现有技术水平相当。

##### URL
[https://arxiv.org/abs/1606.01280](https://arxiv.org/abs/1606.01280)

##### PDF
[https://arxiv.org/pdf/1606.01280](https://arxiv.org/pdf/1606.01280)

