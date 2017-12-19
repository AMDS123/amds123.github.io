---
layout: post
title: "VQS: Linking Segmentations to Questions and Answers for Supervised Attention in VQA and Question-Focused Semantic Segmentation"
date: 2017-08-15 20:47:02
categories: arXiv_CV
tags: arXiv_CV QA Segmentation Attention Semantic_Segmentation Language_Model VQA
author: Chuang Gan, Yandong Li, Haoxiang Li, Chen Sun, Boqing Gong
mathjax: true
---

* content
{:toc}

##### Abstract
Rich and dense human labeled datasets are among the main enabling factors for the recent advance on vision-language understanding. Many seemingly distant annotations (e.g., semantic segmentation and visual question answering (VQA)) are inherently connected in that they reveal different levels and perspectives of human understandings about the same visual scenes --- and even the same set of images (e.g., of COCO). The popularity of COCO correlates those annotations and tasks. Explicitly linking them up may significantly benefit both individual tasks and the unified vision and language modeling. We present the preliminary work of linking the instance segmentations provided by COCO to the questions and answers (QAs) in the VQA dataset, and name the collected links visual questions and segmentation answers (VQS). They transfer human supervision between the previously separate tasks, offer more effective leverage to existing problems, and also open the door for new research problems and models. We study two applications of the VQS data in this paper: supervised attention for VQA and a novel question-focused semantic segmentation task. For the former, we obtain state-of-the-art results on the VQA real multiple-choice task by simply augmenting the multilayer perceptrons with some attention features that are learned using the segmentation-QA links as explicit supervision. To put the latter in perspective, we study two plausible methods and compare them to an oracle method assuming that the instance segmentations are given at the test stage.

##### Abstract (translated by Google)
丰富和密集的人类标记数据集是最近推进视觉语言理解的主要促成因素之一。许多看起来很遥远的注释（如语义分割和视觉问题回答（VQA））本质上是连接在一起的，因为它们揭示了人类对相同视觉场景的理解的不同层次和观点---甚至是同一组图像（例如COCO）。 COCO的流行与这些注释和任务相关联。明确地将它们联系起来可能对单个任务和统一的视觉和语言建模都有很大的好处。我们介绍将COCO提供的实例分割与VQA数据集中的问题和答案（QA）连接起来的初步工作，并将收集到的链接视觉问题和分词答案命名为VQS。它们将以前各项任务之间的人员监督转移到了一起，为现有问题提供了更有效的杠杆作用，也为新的研究问题和模式打开了大门。本文研究了VQS数据在本文中的两个应用：VQA的监督注意和一个新的以问题为中心的语义分割任务。对于前者，我们在VQA真正的多项选择任务中获得最新的结果，只需增加多层感知器，使用分割-QA链接学习的一些注意特征作为明确的监督。为了说明后者，我们研究了两种似是而非的方法，并将其与一种预测方法进行比较，假设实例分割是在测试阶段给出的。

##### URL
[https://arxiv.org/abs/1708.04686](https://arxiv.org/abs/1708.04686)

##### PDF
[https://arxiv.org/pdf/1708.04686](https://arxiv.org/pdf/1708.04686)

