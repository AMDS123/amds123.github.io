---
layout: post
title: "Scene Graph Generation from Objects, Phrases and Region Captions"
date: 2017-09-15 05:05:29
categories: arXiv_CV
tags: arXiv_CV Object_Detection Caption Detection Relation
author: Yikang Li, Wanli Ouyang, Bolei Zhou, Kun Wang, Xiaogang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Object detection, scene graph generation and region captioning, which are three scene understanding tasks at different semantic levels, are tied together: scene graphs are generated on top of objects detected in an image with their pairwise relationship predicted, while region captioning gives a language description of the objects, their attributes, relations, and other context information. In this work, to leverage the mutual connections across semantic levels, we propose a novel neural network model, termed as Multi-level Scene Description Network (denoted as MSDN), to solve the three vision tasks jointly in an end-to-end manner. Objects, phrases, and caption regions are first aligned with a dynamic graph based on their spatial and semantic connections. Then a feature refining structure is used to pass messages across the three levels of semantic tasks through the graph. We benchmark the learned model on three tasks, and show the joint learning across three tasks with our proposed method can bring mutual improvements over previous models. Particularly, on the scene graph generation task, our proposed method outperforms the state-of-art method with more than 3% margin.

##### Abstract (translated by Google)
对象检测，场景图形生成和区域字幕是不同语义层次上的三种场景理解任务，它们被捆绑在一起：在图像中检测到的物体之上生成场景图形，预测它们的配对关系，区域字幕给出语言描述对象，属性，关系和其他上下文信息。在这项工作中，为了利用语义层次上的相互关系，我们提出了一种新的神经网络模型，称为多级场景描述网络（表示为MSDN），以端到端的方式共同解决三个视觉任务。对象，短语和标题区域首先根据其空间和语义连接与动态图形对齐。然后使用特征细化结构来通过图表在三个语义任务级别上传递消息。我们在三个任务上对学习模型进行了基准测试，并且使用我们提出的方法显示了三个任务间的联合学习可以带来与之前的模型相互的改进特别是在场景图生成任务中，我们提出的方法比现有技术的方法优于3％的余量。

##### URL
[https://arxiv.org/abs/1707.09700](https://arxiv.org/abs/1707.09700)

##### PDF
[https://arxiv.org/pdf/1707.09700](https://arxiv.org/pdf/1707.09700)

