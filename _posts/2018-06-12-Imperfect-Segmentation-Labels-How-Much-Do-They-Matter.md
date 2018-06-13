---
layout: post
title: "Imperfect Segmentation Labels: How Much Do They Matter?"
date: 2018-06-12 15:54:42
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Classification
author: Nicholas Heller, Joshua Dean, Nikolaos Papanikolopoulos
mathjax: true
---

* content
{:toc}

##### Abstract
Labeled datasets for semantic segmentation are imperfect, especially in medical imaging where borders are often subtle or ill-defined. Little work has been done to analyze the effect that label errors have on the performance of segmentation methodologies. Here we present a large-scale study of model performance in the presence of varying types and degrees of error in training data. We trained U-Net, SegNet, and FCN32 several times for liver segmentation with 10 different modes of ground-truth perturbation. Our results show that for each architecture, performance steadily declines with boundary-localized errors, however, U-Net was significantly more robust to jagged boundary errors than the other architectures. We also found that each architecture was very robust to non-boundary-localized errors, suggesting that boundary-localized errors are fundamentally different and more challenging problem than random label errors in a classification setting.

##### Abstract (translated by Google)
用于语义分割的标记数据集不完善，特别是在边界常常微妙或不明确的医学成像中。已经做了很少的工作来分析标签错误对分割方法性能的影响。在这里我们展示了一个模型性能的大规模研究，在训练数据中存在不同类型和程度的误差。我们几次用U-Net，SegNet和FCN32训练了10种不同模式的地面真实扰动的肝脏分割。我们的结果显示，对于每种体系结构，性能会随着边界局部化错误而稳步下降，但是，U-Net比锯齿状边界错误显着强于其他体系结构。我们还发现，每种架构对于非边界局部化错误都非常稳健，这表明边界局部化错误与分类环境中的随机标签错误相比，具有根本性的差异和更具挑战性的问题。

##### URL
[http://arxiv.org/abs/1806.04618](http://arxiv.org/abs/1806.04618)

##### PDF
[http://arxiv.org/pdf/1806.04618](http://arxiv.org/pdf/1806.04618)

