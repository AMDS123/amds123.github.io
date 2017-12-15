---
layout: post
title: "Neural Probabilistic Model for Non-projective MST Parsing"
date: 2017-09-03 21:12:40
categories: arXiv_SD
tags: arXiv_SD RNN
author: Xuezhe Ma, Eduard Hovy
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a probabilistic parsing model, which defines a proper conditional probability distribution over non-projective dependency trees for a given sentence, using neural representations as inputs. The neural network architecture is based on bi-directional LSTM-CNNs which benefits from both word- and character-level representations automatically, by using combination of bidirectional LSTM and CNN. On top of the neural network, we introduce a probabilistic structured layer, defining a conditional log-linear model over non-projective trees. We evaluate our model on 17 different datasets, across 14 different languages. By exploiting Kirchhoff's Matrix-Tree Theorem (Tutte, 1984), the partition functions and marginals can be computed efficiently, leading to a straight-forward end-to-end model training procedure via back-propagation. Our parser achieves state-of-the-art parsing performance on nine datasets.

##### Abstract (translated by Google)
在本文中，我们提出了一种概率分析模型，它使用神经表示作为输入，为给定句子定义非投影依赖树的合适的条件概率分布。神经网络体系结构是基于双向LSTM-CNN，通过使用双向LSTM和CNN的组合，自动获得词和字符级的表示。在神经网络之上，我们引入了概率结构化层，定义了非射影树上的条件对数线性模型。我们使用14种不同的语言在17个不同的数据集上评估我们的模型。通过利用基尔霍夫的矩阵树定理（Tutte，1984），可以高效地计算分割函数和边界值，从而通过反向传播得到直接的端到端模型训练过程。我们的解析器在九个数据集上实现了最先进的解析性能。

##### URL
[https://arxiv.org/abs/1701.00874](https://arxiv.org/abs/1701.00874)

##### PDF
[https://arxiv.org/pdf/1701.00874](https://arxiv.org/pdf/1701.00874)

