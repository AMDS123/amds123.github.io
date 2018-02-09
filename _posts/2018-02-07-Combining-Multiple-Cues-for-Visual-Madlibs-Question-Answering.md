---
layout: post
title: "Combining Multiple Cues for Visual Madlibs Question Answering"
date: 2018-02-07 23:28:36
categories: arXiv_CV
tags: arXiv_CV Embedding Optimization Classification Prediction Relation VQA Recognition
author: Tatiana Tommasi, Arun Mallya, Bryan Plummer, Svetlana Lazebnik, Alexander C. Berg, Tamara L. Berg
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents an approach for answering fill-in-the-blank multiple choice questions from the Visual Madlibs dataset. Instead of generic and commonly used representations trained on the ImageNet classification task, our approach employs a combination of networks trained for specialized tasks such as scene recognition, person activity classification, and attribute prediction. We also present a method for localizing phrases from candidate answers in order to provide spatial support for feature extraction. We map each of these features, together with candidate answers, to a joint embedding space through normalized canonical correlation analysis (nCCA). Finally, we solve an optimization problem to learn to combine scores from nCCA models trained on multiple cues to select the best answer. Extensive experimental results show a significant improvement over the previous state of the art and confirm that answering questions from a wide range of types benefits from examining a variety of image cues and carefully choosing the spatial support for feature extraction.

##### Abstract (translated by Google)
本文介绍了一种从Visual Madlibs数据集中回答填空题的方法。我们的方法不是使用在ImageNet分类任务上训练的通用和常用表示，而是使用针对特定任务（如场景识别，人员活动分类和属性预测）进行训练的网络组合。我们还提出了一种从候选答案中定位短语的方法，以便为特征提取提供空间支持。我们通过归一化典型相关分析（nCCA）将每个这些特征与候选答案一起映射到联合嵌入空间。最后，我们解决一个优化问题，学习结合来自多个线索训练的nCCA模型的分数来选择最佳答案。广泛的实验结果显示了与先前的技术水平相比的显着改进，并确认回答来自各种类型的问题从检查各种图像提示并仔细选择用于特征提取的空间支持中受益。

##### URL
[http://arxiv.org/abs/1611.00393](http://arxiv.org/abs/1611.00393)

##### PDF
[http://arxiv.org/pdf/1611.00393](http://arxiv.org/pdf/1611.00393)

