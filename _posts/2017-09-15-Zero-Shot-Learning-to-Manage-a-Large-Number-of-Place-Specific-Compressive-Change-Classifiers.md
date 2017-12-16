---
layout: post
title: "Zero-Shot Learning to Manage a Large Number of Place-Specific Compressive Change Classifiers"
date: 2017-09-15 20:43:40
categories: arXiv_CV
tags: arXiv_CV Knowledge Detection
author: Tanaka Kanji
mathjax: true
---

* content
{:toc}

##### Abstract
With recent progress in large-scale map maintenance and long-term map learning, the task of change detection on a large-scale map from a visual image captured by a mobile robot has become a problem of increasing criticality. Previous approaches for change detection are typically based on image differencing and require the memorization of a prohibitively large number of mapped images in the above context. In contrast, this study follows the recent, efficient paradigm of change-classifier-learning and specifically employs a collection of place-specific change classifiers. Our change-classifier-learning algorithm is based on zero-shot learning (ZSL) and represents a place-specific change classifier by its training examples mined from an external knowledge base (EKB). The proposed algorithm exhibits several advantages. First, we are required to memorize only training examples (rather than the classifier itself), which can be further compressed in the form of bag-of-words (BoW). Secondly, we can incorporate the most recent map into the classifiers by straightforwardly adding or deleting a few training examples that correspond to these classifiers. Thirdly, we can share the BoW vocabulary with other related task scenarios (e.g., BoW-based self-localization), wherein the vocabulary is generally designed as a rich, continuously growing, and domain-adaptive knowledge base. In our contribution, the proposed algorithm is applied and evaluated on a practical long-term cross-season change detection system that consists of a large number of place-specific object-level change classifiers.

##### Abstract (translated by Google)
随着大规模地图维护和长期地图学习的最新进展，从移动机器人捕获的视觉图像的大规模地图上变化检测的任务已经成为增加关键性的问题。先前的用于变化检测的方法通常基于图像差异，并且需要在上述上下文中记忆大量的映射图像。相比之下，这项研究遵循最近的改变 - 分类器学习的有效范例，并特别使用了一系列特定于地点的变化分类器。我们的改变分类器学习算法基于零点学习（ZSL），并通过从外部知识库（EKB）中挖掘出来的训练样例代表特定地点的变化分类器。所提出的算法显示出几个优点。首先，我们只需要记住训练样本（而不是分类器本身），这些样本可以进一步压缩成文字袋（BoW）的形式。其次，通过直接添加或删除与这些分类器相对应的几个训练样例，我们可以将最近的映射合并到分类器中。第三，我们可以将BoW词汇与其他相关的任务场景（例如基于BoW的自我定位）共享，其中词汇一般被设计为丰富的，不断增长的和领域适应性的知识库。在我们的贡献中，所提出的算法被应用和评估在一个实际的长期交叉季节变化检测系统，由大量的特定于地点的对象级变化分类器组成。

##### URL
[https://arxiv.org/abs/1709.05397](https://arxiv.org/abs/1709.05397)

##### PDF
[https://arxiv.org/pdf/1709.05397](https://arxiv.org/pdf/1709.05397)

