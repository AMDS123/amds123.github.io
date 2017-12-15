---
layout: post
title: "Chains of Reasoning over Entities, Relations, and Text using Recurrent Neural Networks"
date: 2017-05-01 14:10:43
categories: arXiv_CL
tags: arXiv_CL Sparse Knowledge Attention Inference RNN Prediction Relation
author: Rajarshi Das, Arvind Neelakantan, David Belanger, Andrew McCallum
mathjax: true
---

* content
{:toc}

##### Abstract
Our goal is to combine the rich multistep inference of symbolic logical reasoning with the generalization capabilities of neural networks. We are particularly interested in complex reasoning about entities and relations in text and large-scale knowledge bases (KBs). Neelakantan et al. (2015) use RNNs to compose the distributed semantics of multi-hop paths in KBs; however for multiple reasons, the approach lacks accuracy and practicality. This paper proposes three significant modeling advances: (1) we learn to jointly reason about relations, entities, and entity-types; (2) we use neural attention modeling to incorporate multiple paths; (3) we learn to share strength in a single RNN that represents logical composition across all relations. On a largescale Freebase+ClueWeb prediction task, we achieve 25% error reduction, and a 53% error reduction on sparse relations due to shared strength. On chains of reasoning in WordNet we reduce error in mean quantile by 84% versus previous state-of-the-art. The code and data are available at this https URL

##### Abstract (translated by Google)
我们的目标是将符号逻辑推理的丰富的多步推理与神经网络的泛化能力相结合。我们特别感兴趣的是关于文本和大规模知识库（KB）中的实体和关系的复杂推理。 Neelakantan等人（2015）使用RNN构成KB中多跳路径的分布式语义;然而由于多种原因，这种方法缺乏准确性和实用性。本文提出了三个重要的建模进展：（1）我们学会了关于关系，实体和实体类型的共同原因; （2）我们使用神经注意力模型来结合多个路径; （3）我们学会在单一的RNN中分享代表所有关系中逻辑构成的力量。在大规模Freebase + ClueWeb预测任务中，由于共享强度，我们实现了25％的错误减少和53％的稀疏关系错误减少。在WordNet的推理链中，我们将平均分位数的误差减少了84％，而以前的技术水平则是这样。代码和数据可在此https网址获得

##### URL
[https://arxiv.org/abs/1607.01426](https://arxiv.org/abs/1607.01426)

##### PDF
[https://arxiv.org/pdf/1607.01426](https://arxiv.org/pdf/1607.01426)

