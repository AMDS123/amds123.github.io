---
layout: post
title: "End-to-End Neural Entity Linking"
date: 2018-08-23 11:16:57
categories: arXiv_CL
tags: arXiv_CL Embedding Detection
author: Nikolaos Kolitsas, Octavian-Eugen Ganea, Thomas Hofmann
mathjax: true
---

* content
{:toc}

##### Abstract
Entity Linking (EL) is an essential task for semantic text understanding and information extraction. Popular methods separately address the Mention Detection (MD) and Entity Disambiguation (ED) stages of EL, without leveraging their mutual dependency. We here propose the first neural end-to-end EL system that jointly discovers and links entities in a text document. The main idea is to consider all possible spans as potential mentions and learn contextual similarity scores over their entity candidates that are useful for both MD and ED decisions. Key components are context-aware mention embeddings, entity embeddings and a probabilistic mention - entity map, without demanding other engineered features. Empirically, we show that our end-to-end method significantly outperforms popular systems on the Gerbil platform when enough training data is available. Conversely, if testing datasets follow different annotation conventions compared to the training set (e.g. queries/ tweets vs news documents), our ED model coupled with a traditional NER system offers the best or second best EL accuracy.

##### Abstract (translated by Google)
实体链接（EL）是语义文本理解和信息提取的基本任务。流行的方法分别解决了EL的提及检测（MD）和实体消歧（ED）阶段，而没有利用它们的相互依赖性。我们在此提出第一个神经端到端EL系统，它共同发现并链接文本文档中的实体。主要思想是将所有可能的跨度视为潜在的提及，并学习对其实体候选人的上下文相似性得分，这对MD和ED决策都有用。关键组件是上下文感知提及嵌入，实体嵌入和概率提及 - 实体映射，而不需要其他工程特性。根据经验，我们表明，当有足够的训练数据时，我们的端到端方法明显优于Gerbil平台上的流行系统。相反，如果测试数据集遵循与训练集相比不同的注释约定（例如查询/推文与新闻文档），我们的ED模型与传统的NER系统相结合，可提供最佳或次佳的EL精度。

##### URL
[http://arxiv.org/abs/1808.07699](http://arxiv.org/abs/1808.07699)

##### PDF
[http://arxiv.org/pdf/1808.07699](http://arxiv.org/pdf/1808.07699)

