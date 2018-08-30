---
layout: post
title: "Towards Semi-Supervised Learning for Deep Semantic Role Labeling"
date: 2018-08-28 20:55:41
categories: arXiv_CL
tags: arXiv_CL Inference RNN
author: Sanket Vaibhav Mehta, Jay Yoon Lee, Jaime Carbonell
mathjax: true
---

* content
{:toc}

##### Abstract
Neural models have shown several state-of-the-art performances on Semantic Role Labeling (SRL). However, the neural models require an immense amount of semantic-role corpora and are thus not well suited for low-resource languages or domains. The paper proposes a semi-supervised semantic role labeling method that outperforms the state-of-the-art in limited SRL training corpora. The method is based on explicitly enforcing syntactic constraints by augmenting the training objective with a syntactic-inconsistency loss component and uses SRL-unlabeled instances to train a joint-objective LSTM. On CoNLL-2012 English section, the proposed semi-supervised training with 1%, 10% SRL-labeled data and varying amounts of SRL-unlabeled data achieves +1.58, +0.78 F1, respectively, over the pre-trained models that were trained on SOTA architecture with ELMo on the same SRL-labeled data. Additionally, by using the syntactic-inconsistency loss on inference time, the proposed model achieves +3.67, +2.1 F1 over pre-trained model on 1%, 10% SRL-labeled data, respectively.

##### Abstract (translated by Google)
神经模型已经在语义角色标签（SRL）上展示了几种最先进的表现。然而，神经模型需要大量的语义角色语料库，因此不适合低资源语言或域。本文提出了一种半监督语义角色标注方法，该方法在有限的SRL训练语料库中优于现有技术。该方法基于通过使用语法 - 不一致性损失组件增加训练目标并使用SRL未标记的实例来训练联合目标LSTM来明确地实施句法约束。在CoNLL-2012英语版块中，提议的半监督训练包含1％，10％SRL标记数据和不同数量的SRL未标记数据，分别比经过训练的预训练模型达到+1.58，+ 0.78 F1在ELTA架构上使用ELMo在相同的SRL标记数据上。此外，通过在推理时间上使用句法不一致性损失，所提出的模型分别在1％，10％SRL标记数据上比预训练模型达到+ 3.67，+ 2.1 F1。

##### URL
[http://arxiv.org/abs/1808.09543](http://arxiv.org/abs/1808.09543)

##### PDF
[http://arxiv.org/pdf/1808.09543](http://arxiv.org/pdf/1808.09543)

