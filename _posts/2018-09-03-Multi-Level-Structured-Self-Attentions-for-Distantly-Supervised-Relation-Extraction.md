---
layout: post
title: "Multi-Level Structured Self-Attentions for Distantly Supervised Relation Extraction"
date: 2018-09-03 19:39:20
categories: arXiv_CL
tags: arXiv_CL Relation_Extraction Attention RNN Relation
author: Jinhua Du, Jingguang Han, Andy Way, Dadong Wan
mathjax: true
---

* content
{:toc}

##### Abstract
Attention mechanisms are often used in deep neural networks for distantly supervised relation extraction (DS-RE) to distinguish valid from noisy instances. However, traditional 1-D vector attention models are insufficient for the learning of different contexts in the selection of valid instances to predict the relationship for an entity pair. To alleviate this issue, we propose a novel multi-level structured (2-D matrix) self-attention mechanism for DS-RE in a multi-instance learning (MIL) framework using bidirectional recurrent neural networks. In the proposed method, a structured word-level self-attention mechanism learns a 2-D matrix where each row vector represents a weight distribution for different aspects of an instance regarding two entities. Targeting the MIL issue, the structured sentence-level attention learns a 2-D matrix where each row vector represents a weight distribution on selection of different valid in-stances. Experiments conducted on two publicly available DS-RE datasets show that the proposed framework with a multi-level structured self-attention mechanism significantly outperform state-of-the-art baselines in terms of PR curves, P@N and F1 measures.

##### Abstract (translated by Google)
注意机制通常用于深度神经网络中，用于远程监督关系提取（DS-RE）以区分有效和有噪声的实例。然而，传统的一维向量注意模型不足以在选择有效实例时学习不同的上下文来预测实体对的关系。为了缓解这个问题，我们在使用双向递归神经网络的多实例学习（MIL）框架中为DS-RE提出了一种新颖的多级结构化（2-D矩阵）自注意机制。在所提出的方法中，结构化的单词级自我关注机制学习2-D矩阵，其中每个行向量表示关于两个实体的实例的不同方面的权重分布。针对MIL问题，结构化句子级注意力学习二​​维矩阵，其中每个行向量表示选择不同有效实例时的权重分布。在两个公开可用的DS-RE数据集上进行的实验表明，所提出的具有多级结构化自我关注机制的框架在PR曲线，P @ N和F1测量方面明显优于最先进的基线。

##### URL
[http://arxiv.org/abs/1809.00699](http://arxiv.org/abs/1809.00699)

##### PDF
[http://arxiv.org/pdf/1809.00699](http://arxiv.org/pdf/1809.00699)

