---
layout: post
title: "Neural Relation Extraction via Inner-Sentence Noise Reduction and Transfer Learning"
date: 2018-08-21 02:15:05
categories: arXiv_CL
tags: arXiv_CL Knowledge Relation_Extraction Attention Transfer_Learning Classification Relation
author: Tianyi Liu, Xinsong Zhang, Wanhao Zhou, Weijia Jia
mathjax: true
---

* content
{:toc}

##### Abstract
Extracting relations is critical for knowledge base completion and construction in which distant supervised methods are widely used to extract relational facts automatically with the existing knowledge bases. However, the automatically constructed datasets comprise amounts of low-quality sentences containing noisy words, which is neglected by current distant supervised methods resulting in unacceptable precisions. To mitigate this problem, we propose a novel word-level distant supervised approach for relation extraction. We first build Sub-Tree Parse(STP) to remove noisy words that are irrelevant to relations. Then we construct a neural network inputting the sub-tree while applying the entity-wise attention to identify the important semantic features of relational words in each instance. To make our model more robust against noisy words, we initialize our network with a priori knowledge learned from the relevant task of entity classification by transfer learning. We conduct extensive experiments using the corpora of New York Times(NYT) and Freebase. Experiments show that our approach is effective and improves the area of Precision/Recall(PR) from 0.35 to 0.39 over the state-of-the-art work.

##### Abstract (translated by Google)
提取关系对于知识库的完成和构建至关重要，其中远程监督方法被广泛用于利用现有知识库自动提取关系事实。然而，自动构建的数据集包括含有噪声单词的低质量句子的数量，当前远程监督方法忽略了这些数据，导致不可接受的精确度。为了缓解这个问题，我们提出了一种用于关系提取的新颖的单词级远程监督方法。我们首先构建子树解析（STP）以移除与关系无关的嘈杂字。然后我们构建一个输入子树的神经网络，同时应用实体方面的注意来识别每个实例中关系词的重要语义特征。为了使我们的模型更能抵抗嘈杂的单词，我们使用通过转移学习从实体分类的相关任务中学到的先验知识来初始化我们的网络。我们使用纽约时报（NYT）和Freebase的语料库进行了大量的实验。实验表明，我们的方法是有效的，并且在最先进的工作中将精确/召回（PR）的面积从0.35提高到0.39。

##### URL
[http://arxiv.org/abs/1808.06738](http://arxiv.org/abs/1808.06738)

##### PDF
[http://arxiv.org/pdf/1808.06738](http://arxiv.org/pdf/1808.06738)

