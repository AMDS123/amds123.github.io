---
layout: post
title: "Arabic Multi-Dialect Segmentation: bi-LSTM-CRF vs. SVM"
date: 2017-08-19 19:52:36
categories: arXiv_CL
tags: arXiv_CL Segmentation RNN
author: Mohamed Eldesouki, Younes Samih, Ahmed Abdelali, Mohammed Attia, Hamdy Mubarak, Kareem Darwish, Kallmeyer Laura
mathjax: true
---

* content
{:toc}

##### Abstract
Arabic word segmentation is essential for a variety of NLP applications such as machine translation and information retrieval. Segmentation entails breaking words into their constituent stems, affixes and clitics. In this paper, we compare two approaches for segmenting four major Arabic dialects using only several thousand training examples for each dialect. The two approaches involve posing the problem as a ranking problem, where an SVM ranker picks the best segmentation, and as a sequence labeling problem, where a bi-LSTM RNN coupled with CRF determines where best to segment words. We are able to achieve solid segmentation results for all dialects using rather limited training data. We also show that employing Modern Standard Arabic data for domain adaptation and assuming context independence improve overall results.

##### Abstract (translated by Google)
阿拉伯文分词对于各种NLP应用如机器翻译和信息检索是至关重要的。细分需要将词汇分解为词干，词缀和阴蒂。在本文中，我们比较两种分割四大阿拉伯方言的方法，每种方言只用几千个训练样例。这两种方法涉及将问题提出为排序问题，其中SVM排序器选择最佳分段，并且作为序列标签问题，其中与CRF耦合的双LSTM RNN确定在哪里最佳地分割单词。我们能够使用相当有限的训练数据为所有方言实现可靠的分割结果。我们还表明，使用现代标准阿拉伯数据的领域适应和假设情境独立提高整体结果。

##### URL
[https://arxiv.org/abs/1708.05891](https://arxiv.org/abs/1708.05891)

##### PDF
[https://arxiv.org/pdf/1708.05891](https://arxiv.org/pdf/1708.05891)

