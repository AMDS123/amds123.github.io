---
layout: post
title: "Instance-aware Image and Sentence Matching with Selective Multimodal LSTM"
date: 2016-11-17 06:57:01
categories: arXiv_CV
tags: arXiv_CV Salient Attention RNN
author: Yan Huang, Wei Wang, Liang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Effective image and sentence matching depends on how to well measure their global visual-semantic similarity. Based on the observation that such a global similarity arises from a complex aggregation of multiple local similarities between pairwise instances of image (objects) and sentence (words), we propose a selective multimodal Long Short-Term Memory network (sm-LSTM) for instance-aware image and sentence matching. The sm-LSTM includes a multimodal context-modulated attention scheme at each timestep that can selectively attend to a pair of instances of image and sentence, by predicting pairwise instance-aware saliency maps for image and sentence. For selected pairwise instances, their representations are obtained based on the predicted saliency maps, and then compared to measure their local similarity. By similarly measuring multiple local similarities within a few timesteps, the sm-LSTM sequentially aggregates them with hidden states to obtain a final matching score as the desired global similarity. Extensive experiments show that our model can well match image and sentence with complex content, and achieve the state-of-the-art results on two public benchmark datasets.

##### Abstract (translated by Google)
有效的图像和句子匹配取决于如何很好地衡量他们的全球视觉语义相似度。基于观察到这种全局相似性是由图像（对象）和句子（单词）的成对实例之间的多个局部相似性的复杂聚合产生的，我们提出了一个选择性的多模态长期短期记忆网络（sm-LSTM）意识图像和句子匹配。 sm-LSTM在每个时间步包含一个多模式的上下文调制的注意方案，通过预测图像和句子的成对实例显着图，可以选择性地关注一对图像和句子的实例。对于选定的成对实例，它们的表示是基于预测的显着图获得的，然后进行比较以测量它们的局部相似性。通过在几个时间步长内类似地测量多个局部相似性，sm-LSTM依次将它们与隐藏状态聚合，以获得作为期望的全局相似性的最终匹配分数。大量的实验表明，我们的模型可以很好地匹配图像和复杂内容的句子，并在两个公共基准数据集上达到最新的结果。

##### URL
[https://arxiv.org/abs/1611.05588](https://arxiv.org/abs/1611.05588)

##### PDF
[https://arxiv.org/pdf/1611.05588](https://arxiv.org/pdf/1611.05588)

