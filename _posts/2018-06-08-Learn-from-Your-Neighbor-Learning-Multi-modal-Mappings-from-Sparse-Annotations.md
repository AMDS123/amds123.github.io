---
layout: post
title: "Learn from Your Neighbor: Learning Multi-modal Mappings from Sparse Annotations"
date: 2018-06-08 01:18:10
categories: arXiv_CV
tags: arXiv_CV Sparse Caption Classification Prediction
author: Ashwin Kalyan, Stefan Lee, Anitha Kannan, Dhruv Batra
mathjax: true
---

* content
{:toc}

##### Abstract
Many structured prediction problems (particularly in vision and language domains) are ambiguous, with multiple outputs being correct for an input - e.g. there are many ways of describing an image, multiple ways of translating a sentence; however, exhaustively annotating the applicability of all possible outputs is intractable due to exponentially large output spaces (e.g. all English sentences). In practice, these problems are cast as multi-class prediction, with the likelihood of only a sparse set of annotations being maximized - unfortunately penalizing for placing beliefs on plausible but unannotated outputs. We make and test the following hypothesis - for a given input, the annotations of its neighbors may serve as an additional supervisory signal. Specifically, we propose an objective that transfers supervision from neighboring examples. We first study the properties of our developed method in a controlled toy setup before reporting results on multi-label classification and two image-grounded sequence modeling tasks - captioning and question generation. We evaluate using standard task-specific metrics and measures of output diversity, finding consistent improvements over standard maximum likelihood training and other baselines.

##### Abstract (translated by Google)
许多结构化预测问题（特别是在视觉和语言领域）是不明确的，多个输出对于输入是正确的 - 例如，描述图像有很多种方式，多种翻译句子的方式;然而，由于指数级的大输出空间（例如所有英文句子），详尽注释所有可能输出的适用性是难以处理的。在实践中，这些问题被视为多类预测，可能只有一组稀疏的注释被最大化 - 不幸的是，将信仰置于合理但未注释的输出上。我们制作和测试以下假设 - 对于给定的输入，其邻居的注释可以作为额外的监督信号。具体而言，我们提出了一个目标，即从相邻的例子转移监督我们首先在控制玩具设置中研究我们开发的方法的属性，然后报告多标签分类和两个基于图像的序列建模任务的结果 - 字幕和问题生成。我们使用标准特定任务指标和输出多样性度量进行评估，发现对标准最大似然训练和其他基线的一致改进。

##### URL
[http://arxiv.org/abs/1806.02934](http://arxiv.org/abs/1806.02934)

##### PDF
[http://arxiv.org/pdf/1806.02934](http://arxiv.org/pdf/1806.02934)

