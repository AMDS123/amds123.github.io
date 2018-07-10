---
layout: post
title: "Mammography Assessment using Multi-Scale Deep Classifiers"
date: 2018-06-30 01:26:51
categories: arXiv_CV
tags: arXiv_CV Salient Sparse Segmentation CNN Classification Deep_Learning
author: Ulzee An, Khader Shameer, Lakshmi Subramanian
mathjax: true
---

* content
{:toc}

##### Abstract
Applying deep learning methods to mammography assessment has remained a challenging topic. Dense noise with sparse expressions, mega-pixel raw data resolution, lack of diverse examples have all been factors affecting performance. The lack of pixel-level ground truths have especially limited segmentation methods in pushing beyond approximately bounding regions. We propose a classification approach grounded in high performance tissue assessment as an alternative to all-in-one localization and assessment models that is also capable of pinpointing the causal pixels. First, the objective of the mammography assessment task is formalized in the context of local tissue classifiers. Then, the accuracy of a convolutional neural net is evaluated on classifying patches of tissue with suspicious findings at varying scales, where highest obtained AUC is above $0.9$. The local evaluations of one such expert tissue classifier is used to augment the results of a heatmap regression model and additionally recover the exact causal regions at high resolution as a saliency image suitable for clinical settings.

##### Abstract (translated by Google)
将深度学习方法应用于乳腺X线摄影评估仍然是一个具有挑战性的课具有稀疏表达的密集噪声，百万像素原始数据分辨率，缺乏各种示例都是影响性能的因素。缺少像素级地面事实在推动超出大约边界区域时具有特别有限的分割方法。我们提出了一种基于高性能组织评估的分类方法，作为一体化定位和评估模型的替代方案，该模型也能够精确定位因果像素。首先，乳房摄影评估任务的目标在局部组织分类器的背景下形式化。然后，评估卷积神经网络的准确性，对具有不同尺度的可疑发现的组织斑块进行分类，其中获得的最高AUC高于0.9美元。一个这样的专家组织分类器的局部评估用于增加热图回归模型的结果，并另外以高分辨率恢复精确的因果区域作为适合于临床设置的显着性图像。

##### URL
[http://arxiv.org/abs/1807.03095](http://arxiv.org/abs/1807.03095)

##### PDF
[http://arxiv.org/pdf/1807.03095](http://arxiv.org/pdf/1807.03095)

