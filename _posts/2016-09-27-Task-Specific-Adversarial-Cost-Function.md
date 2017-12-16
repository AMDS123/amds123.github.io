---
layout: post
title: "Task Specific Adversarial Cost Function"
date: 2016-09-27 20:47:42
categories: arXiv_CV
tags: arXiv_CV Adversarial Classification
author: Antonia Creswell, Anil A. Bharath
mathjax: true
---

* content
{:toc}

##### Abstract
The cost function used to train a generative model should fit the purpose of the model. If the model is intended for tasks such as generating perceptually correct samples, it is beneficial to maximise the likelihood of a sample drawn from the model, Q, coming from the same distribution as the training data, P. This is equivalent to minimising the Kullback-Leibler (KL) distance, KL[Q||P]. However, if the model is intended for tasks such as retrieval or classification it is beneficial to maximise the likelihood that a sample drawn from the training data is captured by the model, equivalent to minimising KL[P||Q]. The cost function used in adversarial training optimises the Jensen-Shannon entropy which can be seen as an even interpolation between KL[Q||P] and KL[P||Q]. Here, we propose an alternative adversarial cost function which allows easy tuning of the model for either task. Our task specific cost function is evaluated on a dataset of hand-written characters in the following tasks: Generation, retrieval and one-shot learning.

##### Abstract (translated by Google)
用于训练生成模型的成本函数应符合模型的目的。如果模型用于产生感知上正确的样本等任务，那么从模型中抽取的样本Q与来自与训练数据P相同的分布的可能性最大化是有益的。这相当于最小化Kullback Leibler（KL）距离，KL [Q || P]。但是，如果模型用于检索或分类等任务，则最大化从训练数据中抽取的样本被模型捕获的可能性是有益的，这相当于最小化KL [P || Q]。对抗训练中使用的代价函数优化了Jensen-Shannon熵，它可以看作是KL [Q || P]和KL [P || Q]之间的一个均匀插值。在这里，我们提出了一个替代的对抗成本函数，可以轻松地调整任一模型。我们的任务特定成本函数是在以下任务的手写字符数据集上评估的：生成，检索和一次学习。

##### URL
[https://arxiv.org/abs/1609.08661](https://arxiv.org/abs/1609.08661)

##### PDF
[https://arxiv.org/pdf/1609.08661](https://arxiv.org/pdf/1609.08661)

