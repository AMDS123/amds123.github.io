---
layout: post
title: "TieNet: Text-Image Embedding Network for Common Thorax Disease Classification and Reporting in Chest X-rays"
date: 2018-01-12 22:04:30
categories: arXiv_CV
tags: arXiv_CV Knowledge Attention Embedding RNN Classification
author: Xiaosong Wang, Yifan Peng, Le Lu, Zhiyong Lu, Ronald M. Summers
mathjax: true
---

* content
{:toc}

##### Abstract
Chest X-rays are one of the most common radiological examinations in daily clinical routines. Reporting thorax diseases using chest X-rays is often an entry-level task for radiologist trainees. Yet, reading a chest X-ray image remains a challenging job for learning-oriented machine intelligence, due to (1) shortage of large-scale machine-learnable medical image datasets, and (2) lack of techniques that can mimic the high-level reasoning of human radiologists that requires years of knowledge accumulation and professional training. In this paper, we show the clinical free-text radiological reports can be utilized as a priori knowledge for tackling these two key problems. We propose a novel Text-Image Embedding network (TieNet) for extracting the distinctive image and text representations. Multi-level attention models are integrated into an end-to-end trainable CNN-RNN architecture for highlighting the meaningful text words and image regions. We first apply TieNet to classify the chest X-rays by using both image features and text embeddings extracted from associated reports. The proposed auto-annotation framework achieves high accuracy (over 0.9 on average in AUCs) in assigning disease labels for our hand-label evaluation dataset. Furthermore, we transform the TieNet into a chest X-ray reporting system. It simulates the reporting process and can output disease classification and a preliminary report together. The classification results are significantly improved (6% increase on average in AUCs) compared to the state-of-the-art baseline on an unseen and hand-labeled dataset (OpenI).

##### Abstract (translated by Google)
胸部X光片是日常临床常规中最常见的放射学检查之一。使用胸部X光报告胸部疾病通常是放射科医师的入门级任务。然而，由于（1）大型机器可学习的医学图像数据集短缺，以及（2）缺乏可模仿高分辨率图像数据集的技术，阅读胸部X射线图像仍然是面向学习型机器智能的挑战性工作。需要多年的知识积累和专业培训的人类放射科医生的一级推理。在本文中，我们展示临床自由文本放射学报告可以作为一个先验知识来解决这两个关键问题。我们提出了一种新颖的文本图像嵌入网络（TieNet）来提取独特的图像和文本表示。多层次关注模型被集成到端到端的可训练CNN-RNN架构中，用于突出显示有意义的文本字和图像区域。我们首先将TieNet应用于通过使用从相关报告中提取的图像特征和文本嵌入来对胸部X射线进行分类。所提出的自动标注框架在为我们的手标记评估数据集分配疾病标签时实现了高准确性（AUC平均超过0.9）。此外，我们将TieNet转换成胸部X光报告系统。它模拟报告过程，可以一起输出疾病分类和初步报告。分类结果显着改善（AUCs平均增加6％），与现有技术水平的基线数据相比，在一个看不见的和手动标记的数据集（OpenI）上。

##### URL
[https://arxiv.org/abs/1801.04334](https://arxiv.org/abs/1801.04334)

##### PDF
[https://arxiv.org/pdf/1801.04334](https://arxiv.org/pdf/1801.04334)

