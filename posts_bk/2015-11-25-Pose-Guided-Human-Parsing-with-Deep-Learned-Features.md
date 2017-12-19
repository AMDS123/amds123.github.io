---
layout: post
title: "Pose-Guided Human Parsing with Deep Learned Features"
date: 2015-11-25 02:07:11
categories: arXiv_CV
tags: arXiv_CV Segmentation Inference
author: Fangting Xia, Jun Zhu, Peng Wang, Alan Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
Parsing human body into semantic regions is crucial to human-centric analysis. In this paper, we propose a segment-based parsing pipeline that explores human pose information, i.e. the joint location of a human model, which improves the part proposal, accelerates the inference and regularizes the parsing process at the same time. Specifically, we first generate part segment proposals with respect to human joints predicted by a deep model, then part- specific ranking models are trained for segment selection using both pose-based features and deep-learned part potential features. Finally, the best ensemble of the proposed part segments are inferred though an And-Or Graph. We evaluate our approach on the popular Penn-Fudan pedestrian parsing dataset, and demonstrate the effectiveness of using the pose information for each stage of the parsing pipeline. Finally, we show that our approach yields superior part segmentation accuracy comparing to the state-of-the-art methods.

##### Abstract (translated by Google)
将人体解析为语义区域对于以人为中心的分析至关重要。在本文中，我们提出了一个基于片段的解析流水线，该流水线探索了人体姿态信息，即人体模型的联合位置，从而改善了部分建议，同时加快了推理过程并规范了解析过程。具体而言，我们首先生成关于通过深度模型预测的人体关节的部分分段建议，然后使用基于姿势的特征和深度学习部分潜在特征来针对分段选择训练部分特定的分级模型。最后，通过And-Or图来推断所提出的部分段的最佳集合。我们在流行的Penn-Fudan行人解析数据集上评估了我们的方法，并且演示了在解析流水线的每个阶段使用姿态信息的有效性。最后，我们表明，与最先进的方法相比，我们的方法可以产生出色的部件分段精度。

##### URL
[https://arxiv.org/abs/1508.03881](https://arxiv.org/abs/1508.03881)

##### PDF
[https://arxiv.org/pdf/1508.03881](https://arxiv.org/pdf/1508.03881)

