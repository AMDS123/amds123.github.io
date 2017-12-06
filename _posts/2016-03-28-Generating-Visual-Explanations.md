---
layout: post
title: "Generating Visual Explanations"
date: 2016-03-28 19:54:12
categories: arXiv_CV
tags: arXiv_CV Reinforcement_Learning Caption Recognition
author: Lisa Anne Hendricks, Zeynep Akata, Marcus Rohrbach, Jeff Donahue, Bernt Schiele, Trevor Darrell
mathjax: true
---

* content
{:toc}

##### Abstract
Clearly explaining a rationale for a classification decision to an end-user can be as important as the decision itself. Existing approaches for deep visual recognition are generally opaque and do not output any justification text; contemporary vision-language models can describe image content but fail to take into account class-discriminative image aspects which justify visual predictions. We propose a new model that focuses on the discriminating properties of the visible object, jointly predicts a class label, and explains why the predicted label is appropriate for the image. We propose a novel loss function based on sampling and reinforcement learning that learns to generate sentences that realize a global sentence property, such as class specificity. Our results on a fine-grained bird species classification dataset show that our model is able to generate explanations which are not only consistent with an image but also more discriminative than descriptions produced by existing captioning methods.

##### Abstract (translated by Google)
明确地向最终用户解释分类决策的基本原理与决策本身一样重要。现有的深度视觉识别方法通常是不透明的，不会输出任何理由文本;当代的视觉语言模型可以描述图像内容，但是没有考虑视觉预测合理化的类别识别图像方面。我们提出了一个新的模型，着眼于可见对象的区分属性，联合预测一个类标签，并解释了为什么预测标签适合于图像。我们提出了一种基于抽样和强化学习的新型损失函数，它学习生成实现全局句子属性的句子，例如类特异性。我们在一个细粒度的鸟类分类数据集上的结果表明，我们的模型能够产生不仅与图像一致的解释，而且比现有的字幕方法产生的描述更具有区别性。

##### URL
[https://arxiv.org/abs/1603.08507](https://arxiv.org/abs/1603.08507)

