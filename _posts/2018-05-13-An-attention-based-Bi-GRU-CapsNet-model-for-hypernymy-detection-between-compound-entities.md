---
layout: post
title: "An attention-based Bi-GRU-CapsNet model for hypernymy detection between compound entities"
date: 2018-05-13 06:09:40
categories: arXiv_CL
tags: arXiv_CL Knowledge_Graph Knowledge Attention Detection Relation
author: Qi Wang, Tong Ruan, Yangming Zhou, Daqi Gao, Ping He
mathjax: true
---

* content
{:toc}

##### Abstract
Named entities which composed of multiple continuous words frequently occur in domain-specific knowledge graphs. These entities are usually composable and extensible. Typical examples are names of symptoms and diseases in medical areas. To distinguish these entities from general words, we name them compound entities. Hypernymy detection between compound entities plays an important role in domain-specific knowledge graph construction. Traditional hypernymy detection approaches cannot perform well on compound entities due to the lack of contextual information in texts, and even the absence of compound entities in training sets, i.e. Out-Of-Vocabulary (OOV) problem. In this paper, we present a novel attention-based Bi-GRU-CapsNet model to detect hypernymy relationship between compound entities. Our model integrates several important components. English words or Chinese characters in compound entities are fed into Bidirectional Recurrent Units (Bi-GRUs) to avoid the OOV problem. An attention mechanism is then designed to focus on the differences between two compound entities. Since there are different cases in hypernymy relationship between compound entities, Capsule Network (CapsNet) is finally employed to decide whether the hypernymy relationship exists or not. Experimental results demonstrate the advantages of the proposed model over the state-of-the-art methods both on English and Chinese corpora of symptom and disease pairs.

##### Abstract (translated by Google)
由多个连续词组成的命名实体经常出现在领域特定的知识图中。这些实体通常是可组合和可扩展的。典型的例子是医学领域的症状和疾病的名称。为了区分这些实体与一般词语，我们将它们命名为复合实体。复合实体之间的超视距检测在领域特定的知识图构造中起着重要作用。由于缺乏文本中的上下文信息，甚至在训练集中缺少复合实体，即词外（OOV）问题，所以传统的上位检测方法无法在复合实体上表现良好。在本文中，我们提出了一种新颖的基于注意力的Bi-GRU-CapsNet模型来检测复合实体之间的上位关系。我们的模型集成了几个重要组件。复合实体中的英文单词或汉字被送入双向循环单元（Bi-GRUs）以避免OOV问题。然后设计一个注意机制来关注两个复合实体之间的差异。由于复合实体之间的上位关系存在不同的情况，因此Capsule Network（CapsNet）最终用于决定超合作关系是否存在。实验结果证明了该模型相对于英文和中文症状和疾病对语料库中现有技术方法的优势。

##### URL
[https://arxiv.org/abs/1805.04827](https://arxiv.org/abs/1805.04827)

##### PDF
[https://arxiv.org/pdf/1805.04827](https://arxiv.org/pdf/1805.04827)

