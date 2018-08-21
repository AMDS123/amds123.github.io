---
layout: post
title: "Learning to Compose over Tree Structures via POS Tags"
date: 2018-08-18 11:53:24
categories: arXiv_CL
tags: arXiv_CL RNN Classification
author: Gehui Shen, Zhi-Hong Deng, Ting Huang, Xi Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Recursive Neural Network (RecNN), a type of models which compose words or phrases recursively over syntactic tree structures, has been proven to have superior ability to obtain sentence representation for a variety of NLP tasks. However, RecNN is born with a thorny problem that a shared compositional function for each node of trees can't capture the complex semantic compositionality so that the expressive power of model is limited. In this paper, in order to address this problem, we propose Tag-Guided HyperRecNN/TreeLSTM (TG-HRecNN/TreeLSTM), which introduces hypernetwork into RecNNs to take as inputs Part-of-Speech (POS) tags of word/phrase and generate the semantic composition parameters dynamically. Experimental results on five datasets for two typical NLP tasks show proposed models both obtain significant improvement compared with RecNN and TreeLSTM consistently. Our TG-HTreeLSTM outperforms all existing RecNN-based models and achieves or is competitive with state-of-the-art on four sentence classification benchmarks. The effectiveness of our models is also demonstrated by qualitative analysis.

##### Abstract (translated by Google)
递归神经网络（RecNN），一种在句法树结构上递归地组成单词或短语的模型，已被证明具有获得各种NLP任务的句子表示的卓越能力。然而，RecNN诞生了一个棘手的问题，即每个树节点的共享组合函数无法捕获复杂的语义组合，因此模型的表达能力是有限的。在本文中，为了解决这个问题，我们提出Tag-Guided HyperRecNN / TreeLSTM（TG-HRecNN / TreeLSTM），它将超网络引入RecNNs作为输入词/短语的词性（POS）标签和动态生成语义合成参数。对于两个典型NLP任务的五个数据集的实验结果表明，与RecNN和TreeLSTM相比，所提出的模型都获得了显着的改进。我们的TG-HTreeLSTM优于所有现有的基于RecNN的模型，并且在四个句子分类基准上达到或者具有最新技术水平。定性分析也证明了我们模型的有效性。

##### URL
[http://arxiv.org/abs/1808.06075](http://arxiv.org/abs/1808.06075)

##### PDF
[http://arxiv.org/pdf/1808.06075](http://arxiv.org/pdf/1808.06075)

