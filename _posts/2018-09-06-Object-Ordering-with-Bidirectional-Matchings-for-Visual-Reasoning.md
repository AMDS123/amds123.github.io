---
layout: post
title: "Object Ordering with Bidirectional Matchings for Visual Reasoning"
date: 2018-09-06 16:56:32
categories: arXiv_AI
tags: arXiv_AI Attention Relation
author: Hao Tan, Mohit Bansal
mathjax: true
---

* content
{:toc}

##### Abstract
Visual reasoning with compositional natural language instructions, e.g., based on the newly-released Cornell Natural Language Visual Reasoning (NLVR) dataset, is a challenging task, where the model needs to have the ability to create an accurate mapping between the diverse phrases and the several objects placed in complex arrangements in the image. Further, this mapping needs to be processed to answer the question in the statement given the ordering and relationship of the objects across three similar images. In this paper, we propose a novel end-to-end neural model for the NLVR task, where we first use joint bidirectional attention to build a two-way conditioning between the visual information and the language phrases. Next, we use an RL-based pointer network to sort and process the varying number of unordered objects (so as to match the order of the statement phrases) in each of the three images and then pool over the three decisions. Our model achieves strong improvements (of 4-6% absolute) over the state-of-the-art on both the structured representation and raw image versions of the dataset.

##### Abstract (translated by Google)
使用组合自然语言指令的视觉推理，例如，基于新发布的康奈尔自然语言视觉推理（NLVR）数据集，是一项具有挑战性的任务，其中模型需要能够在不同的短语和不同的短语之间创建准确的映射。几个物体放置在图像中的复杂排列中。此外，在给定跨三个相似图像的对象的排序和关系的情况下，需要处理该映射以回答语句中的问题。在本文中，我们为NLVR任务提出了一种新颖的端到端神经模型，我们首先使用联合双向注意力在视觉信息和语言短语之间建立双向条件。接下来，我们使用基于RL的指针网络对三个图像中的每个图像中的不同数量的无序对象进行排序和处理（以便匹配语句短语的顺序），然​​后汇总这三个决策。我们的模型在数据集的结构化表示和原始图像版本上相对于最先进的技术实现了强大的改进（绝对值为4-6％）。

##### URL
[http://arxiv.org/abs/1804.06870](http://arxiv.org/abs/1804.06870)

##### PDF
[http://arxiv.org/pdf/1804.06870](http://arxiv.org/pdf/1804.06870)

