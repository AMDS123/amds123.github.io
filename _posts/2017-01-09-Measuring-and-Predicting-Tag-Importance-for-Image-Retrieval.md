---
layout: post
title: "Measuring and Predicting Tag Importance for Image Retrieval"
date: 2017-01-09 22:32:36
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Prediction Relation
author: Shangwen Li, Sanjay Purushotham, Chen Chen, Yuzhuo Ren, C.-C. Jay Kuo
mathjax: true
---

* content
{:toc}

##### Abstract
Textual data such as tags, sentence descriptions are combined with visual cues to reduce the semantic gap for image retrieval applications in today's Multimodal Image Retrieval (MIR) systems. However, all tags are treated as equally important in these systems, which may result in misalignment between visual and textual modalities during MIR training. This will further lead to degenerated retrieval performance at query time. To address this issue, we investigate the problem of tag importance prediction, where the goal is to automatically predict the tag importance and use it in image retrieval. To achieve this, we first propose a method to measure the relative importance of object and scene tags from image sentence descriptions. Using this as the ground truth, we present a tag importance prediction model to jointly exploit visual, semantic and context cues. The Structural Support Vector Machine (SSVM) formulation is adopted to ensure efficient training of the prediction model. Then, the Canonical Correlation Analysis (CCA) is employed to learn the relation between the image visual feature and tag importance to obtain robust retrieval performance. Experimental results on three real-world datasets show a significant performance improvement of the proposed MIR with Tag Importance Prediction (MIR/TIP) system over other MIR systems.

##### Abstract (translated by Google)
文本数据（如标签，句子描述）与视觉线索相结合，以减少当今多模式图像检索（MIR）系统中图像检索应用程序的语义差距。然而，在这些系统中，所有标签都被视为同等重要，这可能导致MIR训练期间的视觉和文本模态之间的不一致。这将进一步导致在查询时退化的检索性能。为了解决这个问题，我们研究了标签重要性预测问题，其目标是自动预测标签重要性，并将其用于图像检索。为了达到这个目的，我们首先提出一种从图像文字描述中测量物体和场景标签相对重要性的方法。以此作为基础事实，我们提出了一个标签重要性预测模型来共同开发视觉，语义和上下文线索。采用结构支持向量机（SSVM）公式来保证预测模型的有效训练。然后，采用典型相关分析（CCA）学习图像视觉特征与标签重要性之间的关系，获得鲁棒的检索性能。在三个真实世界的数据集上的实验结果显示，与其他MIR系统相比，使用标签重要性预测（MIR / TIP）系统的所提议的MIR的性能显着提高。

##### URL
[https://arxiv.org/abs/1602.08680](https://arxiv.org/abs/1602.08680)

##### PDF
[https://arxiv.org/pdf/1602.08680](https://arxiv.org/pdf/1602.08680)

