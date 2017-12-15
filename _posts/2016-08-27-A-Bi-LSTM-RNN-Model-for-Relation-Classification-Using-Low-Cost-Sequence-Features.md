---
layout: post
title: "A Bi-LSTM-RNN Model for Relation Classification Using Low-Cost Sequence Features"
date: 2016-08-27 15:41:22
categories: arXiv_CL
tags: arXiv_CL RNN Classification Relation
author: Fei Li, Meishan Zhang, Guohong Fu, Tao Qian, Donghong Ji
mathjax: true
---

* content
{:toc}

##### Abstract
Relation classification is associated with many potential applications in the artificial intelligence area. Recent approaches usually leverage neural networks based on structure features such as syntactic or dependency features to solve this problem. However, high-cost structure features make such approaches inconvenient to be directly used. In addition, structure features are probably domain-dependent. Therefore, this paper proposes a bi-directional long-short-term-memory recurrent-neural-network (Bi-LSTM-RNN) model based on low-cost sequence features to address relation classification. This model divides a sentence or text segment into five parts, namely two target entities and their three contexts. It learns the representations of entities and their contexts, and uses them to classify relations. We evaluate our model on two standard benchmark datasets in different domains, namely SemEval-2010 Task 8 and BioNLP-ST 2016 Task BB3. In the former dataset, our model achieves comparable performance compared with other models using sequence features. In the latter dataset, our model obtains the third best results compared with other models in the official evaluation. Moreover, we find that the context between two target entities plays the most important role in relation classification. Furthermore, statistic experiments show that the context between two target entities can be used as an approximate replacement of the shortest dependency path when dependency parsing is not used.

##### Abstract (translated by Google)
关系分类与人工智能领域的许多潜在应用相关联。最近的方法通常利用基于结构特征（如句法或依赖特征）的神经网络来解决这个问题。但是，高成本的结构特征使得这种方法不便于直接使用。另外，结构特征可能是与域有关的。因此，本文提出了一种基于低成本序列特征的双向长短期记忆递归神经网络（Bi-LSTM-RNN）模型来处理关系分类。该模型将句子或文本片段分为五个部分，即两个目标实体及其三个上下文。它学习实体的表示和它们的上下文，并用它们来分类关系。我们在不同领域的两个标准基准数据集上评估我们的模型，即SemEval-2010任务8和BioNLP-ST 2016任务BB3。在前一个数据集中，我们的模型与使用序列特征的其他模型相比，实现了可比较的性能。在后一个数据集中，我们的模型与官方评估中的其他模型相比，获得了第三个最好的结果。此外，我们发现两个目标实体之间的语境在关系分类中起着最重要的作用。此外，统计实验表明，当不使用依赖关系解析时，两个目标实体之间的上下文可以用作近似替换最短依赖路径。

##### URL
[https://arxiv.org/abs/1608.07720](https://arxiv.org/abs/1608.07720)

##### PDF
[https://arxiv.org/pdf/1608.07720](https://arxiv.org/pdf/1608.07720)

