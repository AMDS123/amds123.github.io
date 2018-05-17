---
layout: post
title: "Contextual Augmentation: Data Augmentation by Words with Paradigmatic Relations"
date: 2018-05-16 09:10:21
categories: arXiv_CL
tags: arXiv_CL Text_Classification CNN RNN Classification Language_Model Relation
author: Sosuke Kobayashi
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel data augmentation for labeled sentences called contextual augmentation. We assume an invariance that sentences are natural even if the words in the sentences are replaced with other words with paradigmatic relations. We stochastically replace words with other words that are predicted by a bi-directional language model at the word positions. Words predicted according to a context are numerous but appropriate for the augmentation of the original words. Furthermore, we retrofit a language model with a label-conditional architecture, which allows the model to augment sentences without breaking the label-compatibility. Through the experiments for six various different text classification tasks, we demonstrate that the proposed method improves classifiers based on the convolutional or recurrent neural networks.

##### Abstract (translated by Google)
我们提出了一种称为情境增强的标记句子的新数据增强。我们假设一个不变性即使句子中的单词被替换为具有范式关系的其他单词，句子也是自然的。我们随机地用单词位置上的双向语言模型预测的其他单词替换单词。根据上下文预测的单词很多，但适合于增加原始单词。此外，我们使用标签条件体系结构改进了语言模型，该模型允许模型在不破坏标签兼容性的情况下扩充句子。通过对六种不同文本分类任务的实验，我们证明了所提出的方法改进了基于卷积或递归神经网络的分类器。

##### URL
[http://arxiv.org/abs/1805.06201](http://arxiv.org/abs/1805.06201)

##### PDF
[http://arxiv.org/pdf/1805.06201](http://arxiv.org/pdf/1805.06201)

