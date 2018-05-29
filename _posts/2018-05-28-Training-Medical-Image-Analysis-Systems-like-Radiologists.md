---
layout: post
title: "Training Medical Image Analysis Systems like Radiologists"
date: 2018-05-28 12:11:03
categories: arXiv_AI
tags: arXiv_AI Classification
author: Gabriel Maicas, Andrew P. Bradley, Jacinto C. Nascimento, Ian Reid, Gustavo Carneiro
mathjax: true
---

* content
{:toc}

##### Abstract
The training of medical image analysis systems using machine learning approaches follows a common script: collect and annotate a large dataset, train the classifier on the training set, and test it on a hold-out test set. This process bears no direct resemblance with radiologist training, which is based on solving a series of tasks of increasing difficulty, where each task involves the use of significantly smaller datasets than those used in machine learning. In this paper, we propose a novel training approach inspired by how radiologists are trained. In particular, we explore the use of meta-training that models a classifier based on a series of tasks. Tasks are selected using teacher-student curriculum learning, where each task consists of simple classification problems containing small training sets. We hypothesize that our proposed meta-training approach can be used to pre-train medical image analysis models. This hypothesis is tested on the automatic breast screening classification from DCE-MRI trained with weakly labeled datasets. The classification performance achieved by our approach is shown to be the best in the field for that application, compared to state of art baseline approaches: DenseNet, multiple instance learning and multi-task learning.

##### Abstract (translated by Google)
使用机器学习方法进行医学图像分析系统的培训遵循一个通用脚本：收集并注释一个大型数据集，在训练集上训练分类器，并在一个保留测试集上测试它。这个过程与放射科医师培训没有直接的相似之处，放射医师培训是基于解决一系列增加难度的任务，其中每个任务涉及比机器学习中使用的小得多的数据集。在本文中，我们提出了一种新的培训方法，受到放射科医师培训的启发。特别是，我们探索了使用基于一系列任务对分类器进行建模的元训练。任务选择使用师生课程学习，每个任务由包含小型训练集的简单分类问题组成。我们假设我们提出的元训练方法可以用于预训练医学图像分析模型。该假设在用弱标记数据集训练的DCE-MRI的自动乳房筛查分类上进行测试。通过我们的方法实现的分类性能在该应用领域表现出最好，与现有技术的基准方法相比：DenseNet，多实例学习和多任务学习。

##### URL
[http://arxiv.org/abs/1805.10884](http://arxiv.org/abs/1805.10884)

##### PDF
[http://arxiv.org/pdf/1805.10884](http://arxiv.org/pdf/1805.10884)

