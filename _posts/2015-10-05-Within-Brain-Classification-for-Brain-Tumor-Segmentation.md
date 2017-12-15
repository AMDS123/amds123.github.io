---
layout: post
title: "Within-Brain Classification for Brain Tumor Segmentation"
date: 2015-10-05 20:32:04
categories: arXiv_CV
tags: arXiv_CV Segmentation Classification
author: Mohammad Havaei, Hugo Larochelle, Philippe Poulin, Pierre-Marc Jodoin
mathjax: true
---

* content
{:toc}

##### Abstract
Purpose: In this paper, we investigate a framework for interactive brain tumor segmentation which, at its core, treats the problem of interactive brain tumor segmentation as a machine learning problem. Methods: This method has an advantage over typical machine learning methods for this task where generalization is made across brains. The problem with these methods is that they need to deal with intensity bias correction and other MRI-specific noise. In this paper, we avoid these issues by approaching the problem as one of within brain generalization. Specifically, we propose a semi-automatic method that segments a brain tumor by training and generalizing within that brain only, based on some minimum user interaction. Conclusion: We investigate how adding spatial feature coordinates (i.e. $i$, $j$, $k$) to the intensity features can significantly improve the performance of different classification methods such as SVM, kNN and random forests. This would only be possible within an interactive framework. We also investigate the use of a more appropriate kernel and the adaptation of hyper-parameters specifically for each brain. Results: As a result of these experiments, we obtain an interactive method whose results reported on the MICCAI-BRATS 2013 dataset are the second most accurate compared to published methods, while using significantly less memory and processing power than most state-of-the-art methods.

##### Abstract (translated by Google)
目的：在本文中，我们研究了一个交互式脑肿瘤分割的框架，其核心是将交互式脑肿瘤分割的问题视为一个机器学习问题。方法：这种方法比普通的机器学习方法有优势。这些方法的问题是他们需要处理强度偏差校正和其他MRI特定的噪音。在本文中，我们通过把这个问题作为脑内概括的一个问题来避免这些问题。具体来说，我们提出了一种半自动方法，通过在大脑内进行训练和推广，基于一些最小的用户交互来分割脑肿瘤。结论：我们研究如何在强度特征上添加空间特征坐标（即$ i $，$ j $，$ k $）可以显着提高不同分类方法（如SVM，kNN和随机森林）的性能。这只能在一个交互框架内进行。我们还研究了更适合的内核的使用和特定于每个大脑的超参数的适应。结果：通过这些实验的结果，我们获得了一种交互式方法，其结果在MICCAI-BRATS 2013数据集上报告的结果与公布的方法相比是第二准确的，同时使用的内存和处理能力要比大多数最先进的方法少得多，艺术方法。

##### URL
[https://arxiv.org/abs/1510.01344](https://arxiv.org/abs/1510.01344)

##### PDF
[https://arxiv.org/pdf/1510.01344](https://arxiv.org/pdf/1510.01344)

