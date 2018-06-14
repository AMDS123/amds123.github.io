---
layout: post
title: "Does Higher Order LSTM Have Better Accuracy for Segmenting and Labeling Sequence Data?"
date: 2018-06-13 02:16:11
categories: arXiv_CL
tags: arXiv_CL RNN Prediction
author: Yi Zhang, Xu Sun, Shuming Ma, Yang Yang, Xuancheng Ren
mathjax: true
---

* content
{:toc}

##### Abstract
Existing neural models usually predict the tag of the current token independent of the neighboring tags. The popular LSTM-CRF model considers the tag dependencies between every two consecutive tags. However, it is hard for existing neural models to take longer distance dependencies of tags into consideration. The scalability is mainly limited by the complex model structures and the cost of dynamic programming during training. In our work, we first design a new model called "high order LSTM" to predict multiple tags for the current token which contains not only the current tag but also the previous several tags. We call the number of tags in one prediction as "order". Then we propose a new method called Multi-Order BiLSTM (MO-BiLSTM) which combines low order and high order LSTMs together. MO-BiLSTM keeps the scalability to high order models with a pruning technique. We evaluate MO-BiLSTM on all-phrase chunking and NER datasets. Experiment results show that MO-BiLSTM achieves the state-of-the-art result in chunking and highly competitive results in two NER datasets.

##### Abstract (translated by Google)
现有的神经模型通常预测当前令牌的标签，而与相邻标签无关。流行的LSTM-CRF模型考虑了每两个连续标签之间的标签依赖关系。然而，现有的神经模型很难将标签的距离依赖性考虑在内。可扩展性主要受复杂模型结构和训练期间动态编程的成本的限制。在我们的工作中，我们首先设计一个名为“高阶LSTM”的新模型来预测当前令牌的多个标签，该标签不仅包含当前标签，还包含之前的几个标签。我们将一次预测中的标签数量称为“订单”。然后我们提出一种称为多阶BiLSTM（MO-BiLSTM）的新方法，它将低阶和高阶LSTM组合在一起。 MO-BiLSTM使用修剪技术保持高阶模型的可扩展性。我们评估全语句块和NER数据集中的MO-BiLSTM。实验结果表明，MO-BiLSTM在两个NER数据集中实现了最新的分块结果和高度竞争的结果。

##### URL
[http://arxiv.org/abs/1711.08231](http://arxiv.org/abs/1711.08231)

##### PDF
[http://arxiv.org/pdf/1711.08231](http://arxiv.org/pdf/1711.08231)

