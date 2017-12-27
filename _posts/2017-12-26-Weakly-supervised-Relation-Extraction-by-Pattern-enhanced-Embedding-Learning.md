---
layout: post
title: "Weakly-supervised Relation Extraction by Pattern-enhanced Embedding Learning"
date: 2017-12-26 02:54:11
categories: arXiv_CL
tags: arXiv_CL Knowledge Relation_Extraction Embedding Relation
author: Meng Qu, Xiang Ren, Yu Zhang, Jiawei Han
mathjax: true
---

* content
{:toc}

##### Abstract
Extracting relations from text corpora is an important task in text mining. It becomes particularly challenging when focusing on weakly-supervised relation extraction, that is, utilizing a few relation instances (i.e., a pair of entities and their relation) as seeds to extract more instances from corpora. Existing distributional approaches leverage the corpus-level co-occurrence statistics of entities to predict their relations, and require large number of labeled instances to learn effective relation classifiers. Alternatively, pattern-based approaches perform bootstrapping or apply neural networks to model the local contexts, but still rely on large number of labeled instances to build reliable models. In this paper, we study integrating the distributional and pattern-based methods in a weakly-supervised setting, such that the two types of methods can provide complementary supervision for each other to build an effective, unified model. We propose a novel co-training framework with a distributional module and a pattern module. During training, the distributional module helps the pattern module discriminate between the informative patterns and other patterns, and the pattern module generates some highly-confident instances to improve the distributional module. The whole framework can be effectively optimized by iterating between improving the pattern module and updating the distributional module. We conduct experiments on two tasks: knowledge base completion with text corpora and corpus-level relation extraction. Experimental results prove the effectiveness of our framework in the weakly-supervised setting.

##### Abstract (translated by Google)
从文本语料中提取关系是文本挖掘的一个重要任务。当关注弱监督关系提取时，即利用一些关系实例（即一对实体及其关系）作为种子从语料库中提取更多的实例，变得特别具有挑战性。现有的分布方法利用实体的语料库级共现统计来预测它们之间的关系，并需要大量的标记实例来学习有效的关系分类器。或者，基于模式的方法执行自举或应用神经网络来建模本地上下文，但仍然依靠大量的标记实例来构建可靠的模型。在本文中，我们研究将分布模式和基于模式的方法结合在一个弱监督的环境中，这两种方法可以相互提供互补的监督，建立一个有效的，统一的模型。我们提出了一个新的分配模块和模式模块的协同培训框架。在训练过程中，分配模块帮助模式模块区分信息模式和其他模式，模式模块产生一些高度自信的实例来改进分配模块。通过迭代改进模式模块和更新分布模块，可以有效地优化整个框架。我们进行了两个任务的实验：知识库完成与文本语料库和语料库级关系抽取。实验结果证明了我们的框架在弱监督环境下的有效性。

##### URL
[http://arxiv.org/abs/1711.03226](http://arxiv.org/abs/1711.03226)

##### PDF
[http://arxiv.org/pdf/1711.03226](http://arxiv.org/pdf/1711.03226)

