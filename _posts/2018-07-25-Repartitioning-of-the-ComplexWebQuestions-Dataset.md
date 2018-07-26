---
layout: post
title: "Repartitioning of the ComplexWebQuestions Dataset"
date: 2018-07-25 14:15:40
categories: arXiv_AI
tags: arXiv_AI
author: Alon Talmor, Jonathan Berant
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, Talmor and Berant (2018) introduced ComplexWebQuestions - a dataset focused on answering complex questions by decomposing them into a sequence of simpler questions and extracting the answer from retrieved web snippets. In their work the authors used a pre-trained reading comprehension (RC) model (Salant and Berant, 2018) to extract the answer from the web snippets. In this short note we show that training a RC model directly on the training data of ComplexWebQuestions reveals a leakage from the training set to the test set that allows to obtain unreasonably high performance. As a solution, we construct a new partitioning of ComplexWebQuestions that does not suffer from this leakage and publicly release it. We also perform an empirical evaluation on these two datasets and show that training a RC model on the training data substantially improves state-of-the-art performance.

##### Abstract (translated by Google)
最近，Talmor和Berant（2018）引入了ComplexWebQuestions--一个数据集，专注于回答复杂问题，将它们分解为一系列简单的问题，并从检索到的网络片段中提取答案。在他们的工作中，作者使用预先训练的阅读理解（RC）模型（Salant和Berant，2018）从网络片段中提取答案。在这篇简短的说明中，我们展示了直接在ComplexWebQuestions的训练数据上训练RC模型，揭示了从训练集到测试集的泄漏，从而获得了不合理的高性能。作为一种解决方案，我们构建了一个新的ComplexWebQuestions分区，它没有遭受这种泄漏并公开发布它。我们还对这两个数据集进行了实证评估，并表明在训练数据上训练RC模型可以显着提高最先进的性能。

##### URL
[http://arxiv.org/abs/1807.09623](http://arxiv.org/abs/1807.09623)

##### PDF
[http://arxiv.org/pdf/1807.09623](http://arxiv.org/pdf/1807.09623)

