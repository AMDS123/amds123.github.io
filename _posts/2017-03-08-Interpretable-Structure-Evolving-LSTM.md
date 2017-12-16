---
layout: post
title: "Interpretable Structure-Evolving LSTM"
date: 2017-03-08 22:09:38
categories: arXiv_CV
tags: arXiv_CV Optimization RNN
author: Xiaodan Liang, Liang Lin, Xiaohui Shen, Jiashi Feng, Shuicheng Yan, Eric P. Xing
mathjax: true
---

* content
{:toc}

##### Abstract
This paper develops a general framework for learning interpretable data representation via Long Short-Term Memory (LSTM) recurrent neural networks over hierarchal graph structures. Instead of learning LSTM models over the pre-fixed structures, we propose to further learn the intermediate interpretable multi-level graph structures in a progressive and stochastic way from data during the LSTM network optimization. We thus call this model the structure-evolving LSTM. In particular, starting with an initial element-level graph representation where each node is a small data element, the structure-evolving LSTM gradually evolves the multi-level graph representations by stochastically merging the graph nodes with high compatibilities along the stacked LSTM layers. In each LSTM layer, we estimate the compatibility of two connected nodes from their corresponding LSTM gate outputs, which is used to generate a merging probability. The candidate graph structures are accordingly generated where the nodes are grouped into cliques with their merging probabilities. We then produce the new graph structure with a Metropolis-Hasting algorithm, which alleviates the risk of getting stuck in local optimums by stochastic sampling with an acceptance probability. Once a graph structure is accepted, a higher-level graph is then constructed by taking the partitioned cliques as its nodes. During the evolving process, representation becomes more abstracted in higher-levels where redundant information is filtered out, allowing more efficient propagation of long-range data dependencies. We evaluate the effectiveness of structure-evolving LSTM in the application of semantic object parsing and demonstrate its advantage over state-of-the-art LSTM models on standard benchmarks.

##### Abstract (translated by Google)
本文开发了一个通过长期短期记忆（LSTM）递归神经网络在层次图结构上学习可解释数据表示的通用框架。我们建议在LSTM网络优化过程中，从数据中以渐进和随机的方式进一步学习中间可解释的多级图结构，而不是在预先固定的结构上学习LSTM模型。因此，我们把这个模型称为结构演化的LSTM。具体来说，从每个节点是小数据元素的初始元素级图形表示开始，结构演进的LSTM通过沿着堆叠的LSTM层随机地合并具有高兼容性的图形节点来逐渐演变多级图表表示。在每个LSTM层，我们估计两个连接节点从它们对应的LSTM门输出的兼容性，这用于产生合并概率。候选图结构相应地生成，其中节点以它们的合并概率被分组成团。然后，我们使用Metropolis-Hasting算法生成新的图结构，通过随机抽样和接受概率来减少陷入局部最优的风险。一旦图形结构被接受，然后通过将分割的派系作为其节点来构建更高级别的图。在不断发展的过程中，在冗余信息被过滤掉的情况下，代表变得更加抽象，允许更有效地传播远程数据相关性。我们评估结构演进的LSTM在语义对象解析应用中的有效性，并证明它在标准基准测试中优于最先进的LSTM模型。

##### URL
[https://arxiv.org/abs/1703.03055](https://arxiv.org/abs/1703.03055)

##### PDF
[https://arxiv.org/pdf/1703.03055](https://arxiv.org/pdf/1703.03055)

