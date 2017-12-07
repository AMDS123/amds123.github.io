---
layout: post
title: "Ensembling Factored Neural Machine Translation Models for Automatic Post-Editing and Quality Estimation"
date: 2017-07-15 12:38:48
categories: arXiv_CL
tags: arXiv_CL NMT
author: Chris Hokamp
mathjax: true
---

* content
{:toc}

##### Abstract
This work presents a novel approach to Automatic Post-Editing (APE) and Word-Level Quality Estimation (QE) using ensembles of specialized Neural Machine Translation (NMT) systems. Word-level features that have proven effective for QE are included as input factors, expanding the representation of the original source and the machine translation hypothesis, which are used to generate an automatically post-edited hypothesis. We train a suite of NMT models that use different input representations, but share the same output space. These models are then ensembled together, and tuned for both the APE and the QE task. We thus attempt to connect the state-of-the-art approaches to APE and QE within a single framework. Our models achieve state-of-the-art results in both tasks, with the only difference in the tuning step which learns weights for each component of the ensemble.

##### Abstract (translated by Google)
这项工作提出了一种新颖的方法来自动编辑后期（APE）和字级质量估计（QE）使用专业神经机器翻译（NMT）系统合奏。已经证明对QE证明有效的字级特征被包括作为输入因子，扩展了原始源的表示和机器翻译假设，其被用于生成自动后编辑的假设。我们训练一组使用不同输入表示的NMT模型，但共享相同的输出空间。然后将这些模型组合在一起，并调整APE和QE任务。因此，我们试图在一个框架内将最先进的方法与APE和QE联系起来。我们的模型在两个任务中都达到了最先进的结果，唯一不同的是在调整步骤中学习了集合中每个组件的权重。

##### URL
[https://arxiv.org/abs/1706.05083](https://arxiv.org/abs/1706.05083)

##### PDF
[https://arxiv.org/pdf/1706.05083](https://arxiv.org/pdf/1706.05083)

