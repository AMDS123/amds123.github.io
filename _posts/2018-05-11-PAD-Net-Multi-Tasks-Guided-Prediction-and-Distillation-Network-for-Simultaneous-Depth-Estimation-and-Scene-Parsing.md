---
layout: post
title: "PAD-Net: Multi-Tasks Guided Prediction-and-Distillation Network for Simultaneous Depth Estimation and Scene Parsing"
date: 2018-05-11 14:12:17
categories: arXiv_CV
tags: arXiv_CV Prediction
author: Dan Xu, Wanli Ouyang, Xiaogang Wang, Nicu Sebe
mathjax: true
---

* content
{:toc}

##### Abstract
Depth estimation and scene parsing are two particularly important tasks in visual scene understanding. In this paper we tackle the problem of simultaneous depth estimation and scene parsing in a joint CNN. The task can be typically treated as a deep multi-task learning problem [42]. Different from previous methods directly optimizing multiple tasks given the input training data, this paper proposes a novel multi-task guided prediction-and-distillation network (PAD-Net), which first predicts a set of intermediate auxiliary tasks ranging from low level to high level, and then the predictions from these intermediate auxiliary tasks are utilized as multi-modal input via our proposed multi-modal distillation modules for the final tasks. During the joint learning, the intermediate tasks not only act as supervision for learning more robust deep representations but also provide rich multi-modal information for improving the final tasks. Extensive experiments are conducted on two challenging datasets (i.e. NYUD-v2 and Cityscapes) for both the depth estimation and scene parsing tasks, demonstrating the effectiveness of the proposed approach.

##### Abstract (translated by Google)
深度估计和场景解析是视觉场景理解中两个特别重要的任务。在本文中，我们解决了联合CNN中同时进行深度估计和场景解析的问题。任务通常可以被看作是一个深度的多任务学习问题[42]。与以前的方法不同，在给定输入训练数据的情况下直接优化多任务，本文提出了一种新型的多任务引导预测 - 精馏网络（PAD-Net），首先预测一组中等辅助任务，从低到高然后通过我们提出的用于最终任务的多模式蒸馏模块将来自这些中间辅助任务的预测用作多模式输入。在联合学习过程中，中间任务不仅充当监督，学习更强大的深层表示，还提供丰富的多模式信息以改进最终任务。针对深度估计和场景分析任务对两个具有挑战性的数据集（即，NYUD-v2和Cityscapes）进行了大量实验，证明了所提出的方法的有效性。

##### URL
[http://arxiv.org/abs/1805.04409](http://arxiv.org/abs/1805.04409)

##### PDF
[http://arxiv.org/pdf/1805.04409](http://arxiv.org/pdf/1805.04409)

