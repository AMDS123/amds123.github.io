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
丰富而密集的人类标记数据集是最近视觉语言理解进展的主要促成因素。许多看似遥远的注释（例如，语义分割和视觉问答（VQA））本质上是相互联系的，因为它们揭示了人类对相同视觉场景的理解的不同层次和视角 - 甚至是同一组图像（例如， COCO）。 COCO的流行与那些注释和任务相关联。明确地将它们联系起来可能会使个人任务和统一的愿景和语言建模受益匪浅。我们提出了将COCO提供的实例分割与VQA数据集中的问题和答案（QA）相关联的初步工作，并将收集的链接命名为视觉问题和分段答案（VQS）。他们在以前单独的任务之间转移人员监督，为现有问题提供更有效的杠杆，并为新的研究问题和模型打开大门。我们在本文中研究了VQS数据的两个应用：监督VQA的注意力和一个新的以问题为中心的语义分割任务。对于前者，我们通过简单地使用分段-QA链接作为显式监督学习的一些注意特征来增加多层感知器，从而获得关于VQA实际多选任务的最新结果。为了对后者进行透视，我们研究了两种似是而非的方法，并将它们与oracle方法进行比较，假设在测试阶段给出了实例分割。

##### URL
[https://arxiv.org/abs/1708.04686](https://arxiv.org/abs/1708.04686)

##### PDF
[https://arxiv.org/pdf/1708.04686](https://arxiv.org/pdf/1708.04686)

