---
layout: post
title: "code2vec: Learning Distributed Representations of Code"
date: 2018-03-28 11:57:57
categories: arXiv_AI
tags: arXiv_AI
author: Uri Alon, Meital Zilberstein, Omer Levy, Eran Yahav
mathjax: true
---

* content
{:toc}

##### Abstract
We present a neural model for representing snippets of code as continuous distributed vectors. The main idea is to represent code as a collection of paths in its abstract syntax tree, and aggregate these paths, in a smart and scalable way, into a single fixed-length $\textit{code vector}$, which can be used to predict semantic properties of the snippet. We demonstrate the effectiveness of our approach by using it to predict a method's name from the vector representation of its body. We evaluate our approach by training a model on a dataset of $14$M methods. We show that code vectors trained on this dataset can predict method names from files that were completely unobserved during training. Furthermore, we show that our model learns useful method name vectors that capture semantic similarities, combinations, and analogies. Comparing previous techniques over the same data set, our approach obtains a relative improvement of over $75\%$, being the first to successfully predict method names based on a large, cross-project, corpus.

##### Abstract (translated by Google)
我们提出了一个神经模型来表示代码段作为连续分布向量。主要思想是将代码表示为其抽象语法树中路径的集合，并将这些路径以智能且​​可扩展的方式聚合为单个固定长度的$ \ textit {代码向量} $，这可用于预测片段的语义属性。我们通过使用它来预测方法的名称从它的身体的向量表示来证明我们方法的有效性。我们通过在$ 14 $ M方法的数据集上训练模型来评估我们的方法。我们显示训练此数据集的代码向量可以从训练期间完全不可观察的文件中预测方法名称。此外，我们显示我们的模型学习捕获语义相似性，组合和类比的有用方法名称向量。通过将以前的技术与同一数据集进行比较，我们的方法获得了超过$ 75％的相对改进，成功率先预测了基于大型跨项目语料库的方法名称。

##### URL
[https://arxiv.org/abs/1803.09473](https://arxiv.org/abs/1803.09473)

##### PDF
[https://arxiv.org/pdf/1803.09473](https://arxiv.org/pdf/1803.09473)

