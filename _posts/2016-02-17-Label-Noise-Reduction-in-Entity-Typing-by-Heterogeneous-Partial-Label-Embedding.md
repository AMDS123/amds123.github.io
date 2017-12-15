---
layout: post
title: "Label Noise Reduction in Entity Typing by Heterogeneous Partial-Label Embedding"
date: 2016-02-17 05:26:47
categories: arXiv_SD
tags: arXiv_SD Knowledge Embedding Relation
author: Xiang Ren, Wenqi He, Meng Qu, Clare R. Voss, Heng Ji, Jiawei Han
mathjax: true
---

* content
{:toc}

##### Abstract
Current systems of fine-grained entity typing use distant supervision in conjunction with existing knowledge bases to assign categories (type labels) to entity mentions. However, the type labels so obtained from knowledge bases are often noisy (i.e., incorrect for the entity mention's local context). We define a new task, Label Noise Reduction in Entity Typing (LNR), to be the automatic identification of correct type labels (type-paths) for training examples, given the set of candidate type labels obtained by distant supervision with a given type hierarchy. The unknown type labels for individual entity mentions and the semantic similarity between entity types pose unique challenges for solving the LNR task. We propose a general framework, called PLE, to jointly embed entity mentions, text features and entity types into the same low-dimensional space where, in that space, objects whose types are semantically close have similar representations. Then we estimate the type-path for each training example in a top-down manner using the learned embeddings. We formulate a global objective for learning the embeddings from text corpora and knowledge bases, which adopts a novel margin-based loss that is robust to noisy labels and faithfully models type correlation derived from knowledge bases. Our experiments on three public typing datasets demonstrate the effectiveness and robustness of PLE, with an average of 25% improvement in accuracy compared to next best method.

##### Abstract (translated by Google)
目前的细粒度实体分类系统使用远程监督与现有的知识库结合，为实体提及分配类别（类型标签）。然而，从知识库中获得的类型标签往往是嘈杂的（即对实体提及的本地情况不正确）。我们定义了一个新的任务，标签降噪实体分类（LNR），作为训练样本的正确类型标签（类型路径）的自动识别，给定了由给定类型层次。单个实体提及的未知类型标签和实体类型之间的语义相似性对解决LNR任务提出了独特的挑战。我们提出了一个称为PLE的通用框架，将实体提及，文本特征和实体类型共同嵌入同一个低维空间，在这个空间中，类型在语义上相近的对象具有相似的表示。然后我们使用学习的嵌入以自顶向下的方式估计每个训练样例的类型路径。我们制定了一个从文本语料库和知识库中学习嵌入的全球目标，它采用了一种新的基于边缘的损失，对噪声标签是鲁棒的，忠实地模拟了从知识库中导出的类型相关性。我们在三个公开的分型数据集上的实验证明了PLE的有效性和鲁棒性，与下一个最好的方法相比，平均精度提高了25％。

##### URL
[https://arxiv.org/abs/1602.05307](https://arxiv.org/abs/1602.05307)

##### PDF
[https://arxiv.org/pdf/1602.05307](https://arxiv.org/pdf/1602.05307)

