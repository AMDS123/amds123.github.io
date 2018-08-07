---
layout: post
title: "Question Type Guided Attention in Visual Question Answering"
date: 2018-07-18 20:43:42
categories: arXiv_CV
tags: arXiv_CV QA Attention VQA Recognition
author: Yang Shi, Tommaso Furlanello, Sheng Zha, Animashree Anandkumar
mathjax: true
---

* content
{:toc}

##### Abstract
Visual Question Answering (VQA) requires integration of feature maps with drastically different structures and focus of the correct regions. Image descriptors have structures at multiple spatial scales, while lexical inputs inherently follow a temporal sequence and naturally cluster into semantically different question types. A lot of previous works use complex models to extract feature representations but neglect to use high-level information summary such as question types in learning. In this work, we propose Question Type-guided Attention (QTA). It utilizes the information of question type to dynamically balance between bottom-up and top-down visual features, respectively extracted from ResNet and Faster R-CNN networks. We experiment with multiple VQA architectures with extensive input ablation studies over the TDIUC dataset and show that QTA systematically improves the performance by more than 5% across multiple question type categories such as "Activity Recognition", "Utility" and "Counting" on TDIUC dataset. By adding QTA on the state-of-art model MCB, we achieve 3% improvement for overall accuracy. Finally, we propose a multi-task extension to predict question types which generalizes QTA to applications that lack of question type, with minimal performance loss.

##### Abstract (translated by Google)
视觉问题回答（VQA）要求对特征图进行整合，使其具有截然不同的结构和正确区域的焦点。图像描述符具有多个空间尺度的结构，而词汇输入固有地遵循时间序列并且自然地聚集到语义上不同的问题类型。许多以前的工作使用复杂模型来提取特征表示，但忽略了使用高级信息摘要，例如学习中的问题类型。在这项工作中，我们提出问题类型引导注意（QTA）。它利用问题类型的信息动态平衡自下而上和自上而下的视觉特征，分别从ResNet和更快的R-CNN网络中提取。我们尝试了多个VQA架构，对TDIUC数据集进行了广泛的输入消融研究，并表明QTA系统地将多个问题类型类别的性能提高了5％以上，例如TDIUC数据集上的“活动识别”，“效用”和“计数” 。通过在最先进的MCB模型上添加QTA，我们可以将整体精度提高3％。最后，我们提出了一个多任务扩展来预测问题类型，这些问题类型将QTA推广到缺乏问题类型的应用程序，并且性能损失最小。

##### URL
[https://arxiv.org/abs/1804.02088](https://arxiv.org/abs/1804.02088)

##### PDF
[https://arxiv.org/pdf/1804.02088](https://arxiv.org/pdf/1804.02088)

