---
layout: post
title: "An attentive neural architecture for joint segmentation and parsing and its application to real estate ads"
date: 2017-09-27 15:50:53
categories: arXiv_CL
tags: arXiv_CL Salient Segmentation Attention Prediction Relation
author: Giannis Bekoulis, Johannes Deleu, Thomas Demeester, Chris Develder
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we develop a relatively simple and effective neural joint model that performs both segmentation and dependency parsing. While the model arose in the context of a particular application, we believe the general idea could be translated to other settings where both (1) entities have to be identified from text, and (2) dependency relationships between them. The application we focus on here is the recently introduced problem of extracting the structured description, which we name property tree, of a real estate property based on the textual advertisement: convert an ad to a tree-structure indicating the buildings, floors, rooms, etc. and how one is part of another. Previous work on the problem focused on a hand-crafted feature-based pipeline approach comprising two different modules, solving the two subtasks of the structured prediction problem: (1) identify important entities of a property (e.g., rooms) from classifieds and (2) structure them into a tree format. In this work, we propose a new joint model that is able to tackle the two tasks simultaneously and construct the property tree by (i) avoiding the error propagation and (ii) exploiting the interactions between the subtasks. For this purpose, we perform an extensive comparative study of the pipeline methods and the new proposed joint model, reporting an improvement of over three percentage points in the overall edge $F_1$ score of the property tree. Also, we have considered several attention methods, to encourage our model to focus on salient tokens during the construction of the property tree. Thus we experimentally demonstrate the usefulness of attentive neural architectures for the proposed joint model, showcasing a further improvement of two percentage points in edge $F_1$ score for our application.

##### Abstract (translated by Google)
在本文中，我们开发了一个相对简单而有效的神经关节模型，执行分割和依赖分析。虽然模型是在特定应用的背景下出现的，但我们相信这个总体思想可以转化为其他的设置，其中（1）实体必须从文本中识别，（2）它们之间的依赖关系。我们在这里关注的应用是最近引入的问题：基于文本广告提取结构化描述（我们称为属性树）的不动产属性：将广告转换为指示建筑物，楼层，房间等的树形结构。等等，以及一个如何是另一个的一部分。以前在这个问题上的工作主要集中在手工制作的基于特征的管道方法上，这个方法包括两个不同的模块，解决了结构化预测问题的两个子任务：（1）识别来自分类的属性的重要实体（例如房间） ）将它们组织成树形格式。在这项工作中，我们提出了一个新的联合模型，能够同时解决这两个任务，通过（i）避免错误传播和（ii）利用子任务之间的交互来构建属性树。为此，我们对流水线方法和新提出的联合模型进行了广泛的比较研究，报告在属性树的整个边缘$ F_1 $得分中提高了三个百分点以上。此外，我们还考虑了几种注意方法，鼓励我们的模型在建设房产树的过程中专注于显着的代币。因此，我们通过实验证明了所提出的联合模型的细致神经架构的有用性，展示了我们的应用在边缘$ F_1 $得分中的两个百分点的进一步改进。

##### URL
[https://arxiv.org/abs/1709.09590](https://arxiv.org/abs/1709.09590)

##### PDF
[https://arxiv.org/pdf/1709.09590](https://arxiv.org/pdf/1709.09590)

