---
layout: post
title: "Not All Pixels Are Equal: Difficulty-aware Semantic Segmentation via Deep Layer Cascade"
date: 2017-04-05 09:58:51
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation
author: Xiaoxiao Li, Ziwei Liu, Ping Luo, Chen Change Loy, Xiaoou Tang
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel deep layer cascade (LC) method to improve the accuracy and speed of semantic segmentation. Unlike the conventional model cascade (MC) that is composed of multiple independent models, LC treats a single deep model as a cascade of several sub-models. Earlier sub-models are trained to handle easy and confident regions, and they progressively feed-forward harder regions to the next sub-model for processing. Convolutions are only calculated on these regions to reduce computations. The proposed method possesses several advantages. First, LC classifies most of the easy regions in the shallow stage and makes deeper stage focuses on a few hard regions. Such an adaptive and 'difficulty-aware' learning improves segmentation performance. Second, LC accelerates both training and testing of deep network thanks to early decisions in the shallow stage. Third, in comparison to MC, LC is an end-to-end trainable framework, allowing joint learning of all sub-models. We evaluate our method on PASCAL VOC and Cityscapes datasets, achieving state-of-the-art performance and fast speed.

##### Abstract (translated by Google)
我们提出了一种新的深层级联（LC）方法来提高语义分割的准确性和速度。与由多个独立模型组成的传统模型级联（MC）不同，LC将单个深层模型视为多个子模型的级联。较早的子模型经过训练，可以处理简单而自信的区域，并逐步将较难的区域推送到下一个子模型进行处理。卷积仅在这些区域上计算以减少计算。所提出的方法具有几个优点。首先，LC将浅层阶段的大部分易区域分类，并将更深的阶段集中在少数几个硬区域。这种适应性和“难度感知”学习改善了分割性能。其次，由于浅层阶段的早期决策，LC加速深层网络的训练和测试。第三，与MC相比，LC是一个端到端的可训练框架，允许联合学习所有子模型。我们在PASCAL VOC和Cityscapes数据集上评估我们的方法，实现了最先进的性能和最快的速度。

##### URL
[https://arxiv.org/abs/1704.01344](https://arxiv.org/abs/1704.01344)

##### PDF
[https://arxiv.org/pdf/1704.01344](https://arxiv.org/pdf/1704.01344)

