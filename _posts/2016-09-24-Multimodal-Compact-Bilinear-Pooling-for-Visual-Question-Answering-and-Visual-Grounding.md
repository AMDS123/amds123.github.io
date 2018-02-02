---
layout: post
title: "Multimodal Compact Bilinear Pooling for Visual Question Answering and Visual Grounding"
date: 2016-09-24 01:58:59
categories: arXiv_CV
tags: arXiv_CV QA Attention VQA
author: Akira Fukui, Dong Huk Park, Daylen Yang, Anna Rohrbach, Trevor Darrell, Marcus Rohrbach
mathjax: true
---

* content
{:toc}

##### Abstract
Modeling textual or visual information with vector representations trained from large language or visual datasets has been successfully explored in recent years. However, tasks such as visual question answering require combining these vector representations with each other. Approaches to multimodal pooling include element-wise product or sum, as well as concatenation of the visual and textual representations. We hypothesize that these methods are not as expressive as an outer product of the visual and textual vectors. As the outer product is typically infeasible due to its high dimensionality, we instead propose utilizing Multimodal Compact Bilinear pooling (MCB) to efficiently and expressively combine multimodal features. We extensively evaluate MCB on the visual question answering and grounding tasks. We consistently show the benefit of MCB over ablations without MCB. For visual question answering, we present an architecture which uses MCB twice, once for predicting attention over spatial features and again to combine the attended representation with the question representation. This model outperforms the state-of-the-art on the Visual7W dataset and the VQA challenge.

##### Abstract (translated by Google)
使用从大型语言或视觉数据集训练的矢量表示对文本或视觉信息进行建模已经成功地探索了近年来。然而，诸如视觉问题回答这样的任务需要将这些向量表示相互组合。多模式汇集的方法包括元素明智的产品或总和，以及视觉和文本表示的连接。我们假设这些方法不如视觉和文本向量的外部产物那样具有表现力。由于外部产品由于其高维度而通常不可行，因此我们建议使用多模式紧凑双线性池（MCB）来有效地并且表达地结合多模式特征。我们广泛地评估MCB在视觉问题解答和接地任务。我们始终如一地显示MCB在没有MCB的情况下消融的好处。对于视觉问题回答，我们提出一个使用MCB两次的体系结构，一次用于预测对空间特征的注意力，并再次将出席的表示与问题表示相结合。这个模型胜过了Visual7W数据集和VQA挑战的最新技术。

##### URL
[https://arxiv.org/abs/1606.01847](https://arxiv.org/abs/1606.01847)

##### PDF
[https://arxiv.org/pdf/1606.01847](https://arxiv.org/pdf/1606.01847)

