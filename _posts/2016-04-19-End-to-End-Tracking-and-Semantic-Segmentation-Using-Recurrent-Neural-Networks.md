---
layout: post
title: "End-to-End Tracking and Semantic Segmentation Using Recurrent Neural Networks"
date: 2016-04-19 14:09:26
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation Tracking Semantic_Segmentation RNN Classification Prediction
author: Peter Ondruska, Julie Dequaire, Dominic Zeng Wang, Ingmar Posner
mathjax: true
---

* content
{:toc}

##### Abstract
In this work we present a novel end-to-end framework for tracking and classifying a robot's surroundings in complex, dynamic and only partially observable real-world environments. The approach deploys a recurrent neural network to filter an input stream of raw laser measurements in order to directly infer object locations, along with their identity in both visible and occluded areas. To achieve this we first train the network using unsupervised Deep Tracking, a recently proposed theoretical framework for end-to-end space occupancy prediction. We show that by learning to track on a large amount of unsupervised data, the network creates a rich internal representation of its environment which we in turn exploit through the principle of inductive transfer of knowledge to perform the task of it's semantic classification. As a result, we show that only a small amount of labelled data suffices to steer the network towards mastering this additional task. Furthermore we propose a novel recurrent neural network architecture specifically tailored to tracking and semantic classification in real-world robotics applications. We demonstrate the tracking and classification performance of the method on real-world data collected at a busy road junction. Our evaluation shows that the proposed end-to-end framework compares favourably to a state-of-the-art, model-free tracking solution and that it outperforms a conventional one-shot training scheme for semantic classification.

##### Abstract (translated by Google)
在这项工作中，我们提出了一个新颖的端到端框架，用于跟踪和分类机器人在复杂的，动态的，只有部分可观察的现实环境中的环境。该方法部署一个循环神经网络来过滤原始激光测量的输入流，以便直接推断物体的位置，以及它们在可见区域和遮挡区域的身份。为了实现这个目标，我们首先使用无监督的深度跟踪（Deep Tracking）来对网络进行训练，这是最近提出的端对端空间占用预测的理论框架。我们表明，通过学习跟踪大量的无监督数据，网络创建了一个丰富的环境内部表示，我们反过来利用感性的知识传导原理来执行它的语义分类任务。因此，我们表明，只有少量的标签数据足以引导网络掌握这个额外的任务。此外，我们提出了一种新颖的经常性神经网络架构，专门针对实际机器人应用中的跟踪和语义分类。我们展示了在繁忙路口收集的实际数据的方法的跟踪和分类性能。我们的评估表明，所提出的端到端框架与最先进的无模型跟踪解决方案相比有优势，并且胜过传统的一次性语义分类训练方案。

##### URL
[https://arxiv.org/abs/1604.05091](https://arxiv.org/abs/1604.05091)

##### PDF
[https://arxiv.org/pdf/1604.05091](https://arxiv.org/pdf/1604.05091)

