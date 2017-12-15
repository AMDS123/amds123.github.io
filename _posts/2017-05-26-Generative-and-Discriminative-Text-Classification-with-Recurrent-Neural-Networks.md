---
layout: post
title: "Generative and Discriminative Text Classification with Recurrent Neural Networks"
date: 2017-05-26 01:27:23
categories: arXiv_SD
tags: arXiv_SD Text_Classification RNN Classification
author: Dani Yogatama, Chris Dyer, Wang Ling, Phil Blunsom
mathjax: true
---

* content
{:toc}

##### Abstract
We empirically characterize the performance of discriminative and generative LSTM models for text classification. We find that although RNN-based generative models are more powerful than their bag-of-words ancestors (e.g., they account for conditional dependencies across words in a document), they have higher asymptotic error rates than discriminatively trained RNN models. However we also find that generative models approach their asymptotic error rate more rapidly than their discriminative counterparts---the same pattern that Ng & Jordan (2001) proved holds for linear classification models that make more naive conditional independence assumptions. Building on this finding, we hypothesize that RNN-based generative classification models will be more robust to shifts in the data distribution. This hypothesis is confirmed in a series of experiments in zero-shot and continual learning settings that show that generative models substantially outperform discriminative models.

##### Abstract (translated by Google)
我们用经验的方式来描述文本分类的区分和生成LSTM模型的性能。我们发现，虽然基于RNN的生成模型比词组的祖先更强大（例如，它们解释了文档中单词之间的条件相关性），但它们具有比差别训练的RNN模型更高的渐近错误率。然而，我们也发现生成模型比它们的区别对应更快地逼近它们的渐近错误率--Ng＆Jordan（2001）证明对于线性分类模型的相同模式使得更加天真的条件独立性假设成立。在这个发现的基础上，我们假设基于RNN的生成分类模型对于数据分布的变化将更加稳健。这个假设在零点和连续学习环境下的一系列实验中得到了证实，这些实验表明生成模型大大优于辨别模型。

##### URL
[https://arxiv.org/abs/1703.01898](https://arxiv.org/abs/1703.01898)

##### PDF
[https://arxiv.org/pdf/1703.01898](https://arxiv.org/pdf/1703.01898)

