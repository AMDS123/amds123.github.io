---
layout: post
title: "Delete, Retrieve, Generate: A Simple Approach to Sentiment and Style Transfer"
date: 2018-04-17 18:59:51
categories: arXiv_CV
tags: arXiv_CV Image_Caption Sentiment Review Adversarial Style_Transfer Caption
author: Juncen Li, Robin Jia, He He, Percy Liang
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the task of text attribute transfer: transforming a sentence to alter a specific attribute (e.g., sentiment) while preserving its attribute-independent content (e.g., changing "screen is just the right size" to "screen is too small"). Our training data includes only sentences labeled with their attribute (e.g., positive or negative), but not pairs of sentences that differ only in their attributes, so we must learn to disentangle attributes from attribute-independent content in an unsupervised way. Previous work using adversarial methods has struggled to produce high-quality outputs. In this paper, we propose simpler methods motivated by the observation that text attributes are often marked by distinctive phrases (e.g., "too small"). Our strongest method extracts content words by deleting phrases associated with the sentence's original attribute value, retrieves new phrases associated with the target attribute, and uses a neural model to fluently combine these into a final output. On human evaluation, our best method generates grammatical and appropriate responses on 22% more inputs than the best previous system, averaged over three attribute transfer datasets: altering sentiment of reviews on Yelp, altering sentiment of reviews on Amazon, and altering image captions to be more romantic or humorous.

##### Abstract (translated by Google)
我们考虑文本属性转移的任务：转换句子以改变特定属性（例如，情绪），同时保留其与属性无关的内容（例如，将“屏幕恰好大小”改为“屏幕太小”）。我们的训练数据仅包括标有其属性的句子（例如，正面或负面），但不包括仅在其属性上不同的句子对，因此我们必须学会以无人监督的方式从属性独立内容中解开属性。以前使用对抗方法的工作一直在努力产生高质量的产出。在本文中，我们提出了更简单的方法，这些方法的动机是观察到文本属性通常用不同的短语标记（例如，“太小”）。我们最强大的方法是通过删除与句子的原始属性值相关联的短语来提取内容单词，检索与目标属性相关联的新短语，并使用神经模型将这些短语流畅地组合成最终输出。在人类评估方面，我们最好的方法产生语法和适当的响应，比最好的先前系统多22％的输入，平均三个属性转移数据集：改变Yelp上的评论情绪，改变亚马逊评论的情绪，以及改变图像标题为更浪漫或幽默。

##### URL
[https://arxiv.org/abs/1804.06437](https://arxiv.org/abs/1804.06437)

##### PDF
[https://arxiv.org/pdf/1804.06437](https://arxiv.org/pdf/1804.06437)

