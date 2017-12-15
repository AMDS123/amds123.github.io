---
layout: post
title: "Data Recombination for Neural Semantic Parsing"
date: 2016-06-11 20:34:09
categories: arXiv_CL
tags: arXiv_CL Knowledge Attention RNN
author: Robin Jia, Percy Liang
mathjax: true
---

* content
{:toc}

##### Abstract
Modeling crisp logical regularities is crucial in semantic parsing, making it difficult for neural models with no task-specific prior knowledge to achieve good results. In this paper, we introduce data recombination, a novel framework for injecting such prior knowledge into a model. From the training data, we induce a high-precision synchronous context-free grammar, which captures important conditional independence properties commonly found in semantic parsing. We then train a sequence-to-sequence recurrent network (RNN) model with a novel attention-based copying mechanism on datapoints sampled from this grammar, thereby teaching the model about these structural properties. Data recombination improves the accuracy of our RNN model on three semantic parsing datasets, leading to new state-of-the-art performance on the standard GeoQuery dataset for models with comparable supervision.

##### Abstract (translated by Google)
清晰的逻辑规律建模在语义分析中至关重要，这使得没有特定任务的神经模型很难获得好的结果。在本文中，我们引入数据重组，这是一种将这种先验知识注入模型的新框架。从训练数据中，我们引入一个高精度的同步上下文无关语法，它捕获语义分析中常见的重要条件独立性。然后，我们训练一个序列 - 序列递归网络（RNN）模型，在这个语法的数据点上采用基于注意力的新型复制机制，从而教授关于这些结构性质的模型。数据重组提高了我们的RNN模型在三个语义分析数据集上的准确性，从而为具有可比较监督的模型的标准GeoQuery数据集带来了全新的最新性能。

##### URL
[https://arxiv.org/abs/1606.03622](https://arxiv.org/abs/1606.03622)

##### PDF
[https://arxiv.org/pdf/1606.03622](https://arxiv.org/pdf/1606.03622)

