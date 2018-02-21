---
layout: post
title: "Interpreting DNN output layer activations: A strategy to cope with unseen data in speech recognition"
date: 2018-02-16 07:42:35
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Recognition
author: Vikramjit Mitra, Horacio Franco
mathjax: true
---

* content
{:toc}

##### Abstract
Unseen data can degrade performance of deep neural net acoustic models. To cope with unseen data, adaptation techniques are deployed. For unlabeled unseen data, one must generate some hypothesis given an existing model, which is used as the label for model adaptation. However, assessing the goodness of the hypothesis can be difficult, and an erroneous hypothesis can lead to poorly trained models. In such cases, a strategy to select data having reliable hypothesis can ensure better model adaptation. This work proposes a data-selection strategy for DNN model adaptation, where DNN output layer activations are used to ascertain the goodness of a generated hypothesis. In a DNN acoustic model, the output layer activations are used to generate target class probabilities. Under unseen data conditions, the difference between the most probable target and the next most probable target is decreased compared to the same for seen data, indicating that the model may be uncertain while generating its hypothesis. This work proposes a strategy to assess a model's performance by analyzing the output layer activations by using a distance measure between the most likely target and the next most likely target, which is used for data selection for performing unsupervised adaptation.

##### Abstract (translated by Google)
看不见的数据会降低深层神经网络声学模型的性能。为了处理不可见的数据，部署了适应技术。对于未标记的未见数据，必须给出一个假设，给出一个现有模型，该模型被用作模型适应的标签。然而，评估假设的好处可能很困难，而错误的假设可能会导致训练不良的模型。在这种情况下，选择具有可靠假设的数据的策略可以确保更好的模型适应性。这项工作提出了DNN模型适应的数据选择策略，其中DNN输出层激活用于确定所产生的假设的好处。在DNN声学模型中，输出层激活用于生成目标类概率。在看不见的数据条件下，最可能的目标与下一个最可能的目标之间的差异与所看到的数据的差异相比减小，表明在产生其假设时模型可能不确定。这项工作提出了一种策略，通过使用最可能的目标与下一个最有可能的目标之间的距离度量来分析输出层激活来评估模型的性能，该目标用于执行无监督适应的数据选择。

##### URL
[http://arxiv.org/abs/1802.06861](http://arxiv.org/abs/1802.06861)

##### PDF
[http://arxiv.org/pdf/1802.06861](http://arxiv.org/pdf/1802.06861)

