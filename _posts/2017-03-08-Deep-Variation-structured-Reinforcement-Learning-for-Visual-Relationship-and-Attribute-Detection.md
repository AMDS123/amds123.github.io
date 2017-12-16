---
layout: post
title: "Deep Variation-structured Reinforcement Learning for Visual Relationship and Attribute Detection"
date: 2017-03-08 22:09:10
categories: arXiv_CV
tags: arXiv_CV Object_Detection Reinforcement_Learning Embedding Image_Classification Classification Prediction Detection Relation
author: Xiaodan Liang, Lisa Lee, Eric P. Xing
mathjax: true
---

* content
{:toc}

##### Abstract
Despite progress in visual perception tasks such as image classification and detection, computers still struggle to understand the interdependency of objects in the scene as a whole, e.g., relations between objects or their attributes. Existing methods often ignore global context cues capturing the interactions among different object instances, and can only recognize a handful of types by exhaustively training individual detectors for all possible relationships. To capture such global interdependency, we propose a deep Variation-structured Reinforcement Learning (VRL) framework to sequentially discover object relationships and attributes in the whole image. First, a directed semantic action graph is built using language priors to provide a rich and compact representation of semantic correlations between object categories, predicates, and attributes. Next, we use a variation-structured traversal over the action graph to construct a small, adaptive action set for each step based on the current state and historical actions. In particular, an ambiguity-aware object mining scheme is used to resolve semantic ambiguity among object categories that the object detector fails to distinguish. We then make sequential predictions using a deep RL framework, incorporating global context cues and semantic embeddings of previously extracted phrases in the state vector. Our experiments on the Visual Relationship Detection (VRD) dataset and the large-scale Visual Genome dataset validate the superiority of VRL, which can achieve significantly better detection results on datasets involving thousands of relationship and attribute types. We also demonstrate that VRL is able to predict unseen types embedded in our action graph by learning correlations on shared graph nodes.

##### Abstract (translated by Google)
尽管在诸如图像分类和检测等视觉感知任务方面取得了进展，但是计算机仍然难以理解整个场景中的对象的相互依赖性，例如对象之间的关系或其属性。现有的方法往往忽略捕捉不同对象实例之间相互作用的全局上下文线索，并且只能通过针对所有可能的关系彻底地训练单独的检测器来识别少数类型。为了捕捉这样的全局相互依赖性，我们提出了一个深度变化结构的强化学习（VRL）框架来依次发现整个图像中的对象关系和属性。首先，使用语言先验来构建定向语义行为图，以提供对象类别，谓词和属性之间的语义相关性的丰富而紧凑的表示。接下来，我们在动作图上使用变化结构遍历，根据当前状态和历史动作为每一步构造一个小的自适应动作集。具体而言，使用歧义感知对象挖掘方案来解决目标检测器无法区分的对象类别之间的语义歧义。然后，我们使用深度RL框架进行连续预测，将全局上下文线索和先前提取的短语的语义嵌入结合到状态向量中。我们对视觉关系检测（VRD）数据集和大型视觉基因组数据集实验验证VRL的优势，从而可以实现对涉及成千上万关系的数据集显著更好的检测结果和属性类型。我们还证明VRL能够通过学习共享图节点上的相关性来预测嵌入在我们行为图中的看不见的类型。

##### URL
[https://arxiv.org/abs/1703.03054](https://arxiv.org/abs/1703.03054)

##### PDF
[https://arxiv.org/pdf/1703.03054](https://arxiv.org/pdf/1703.03054)

