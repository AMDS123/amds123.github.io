---
layout: post
title: "Generating Visual Representations for Zero-Shot Classification"
date: 2017-12-11 16:16:01
categories: arXiv_CV
tags: arXiv_CV Embedding Classification
author: Maxime Bucher (1), St&#xe9;phane Herbin (1), Fr&#xe9;d&#xe9;ric Jurie ((1) Palaiseau)
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the task of learning an image clas-sifier when some categories are defined by semantic descriptions only (e.g. visual attributes) while the others are defined by exemplar images as well. This task is often referred to as the Zero-Shot classification task (ZSC). Most of the previous methods rely on learning a common embedding space allowing to compare visual features of unknown categories with semantic descriptions. This paper argues that these approaches are limited as i) efficient discrimi-native classifiers can't be used ii) classification tasks with seen and unseen categories (Generalized Zero-Shot Classification or GZSC) can't be addressed efficiently. In contrast , this paper suggests to address ZSC and GZSC by i) learning a conditional generator using seen classes ii) generate artificial training examples for the categories without exemplars. ZSC is then turned into a standard supervised learning problem. Experiments with 4 generative models and 5 datasets experimentally validate the approach, giving state-of-the-art results on both ZSC and GZSC.

##### Abstract (translated by Google)
本文讨论了当某些类仅由语义描述（例如视觉属性）定义时，学习图像分类器的任务，而其他类则由示例图像定义。这个任务通常被称为零点分类任务（ZSC）。以前的大多数方法依赖于学习一个共同的嵌入空间，允许将未知类别的视觉特征与语义描述进行比较。本文认为，这些方法是有限的，因为：i）不能使用有效的歧视分类器ii）具有看到和看不见的类别（广义零射击分类或GZSC）的分类任务不能被有效地处理。相反，本文建议通过以下方式来解决ZSC和GZSC：i）使用所看到的类来学习条件生成器; ii）针对没有示例的类别生成人造训练示例。然后ZSC变成一个标准的监督学习问题。用4个生成模型和5个数据集进行实验验证了方法，在ZSC和GZSC上都得到了最新的结果。

##### URL
[http://arxiv.org/abs/1708.06975](http://arxiv.org/abs/1708.06975)

##### PDF
[http://arxiv.org/pdf/1708.06975](http://arxiv.org/pdf/1708.06975)

