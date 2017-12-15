---
layout: post
title: "CloudScan - A configuration-free invoice analysis system using recurrent neural networks"
date: 2017-08-24 13:40:06
categories: arXiv_CL
tags: arXiv_CL RNN
author: Rasmus Berg Palm, Ole Winther, Florian Laws
mathjax: true
---

* content
{:toc}

##### Abstract
We present CloudScan; an invoice analysis system that requires zero configuration or upfront annotation. In contrast to previous work, CloudScan does not rely on templates of invoice layout, instead it learns a single global model of invoices that naturally generalizes to unseen invoice layouts. The model is trained using data automatically extracted from end-user provided feedback. This automatic training data extraction removes the requirement for users to annotate the data precisely. We describe a recurrent neural network model that can capture long range context and compare it to a baseline logistic regression model corresponding to the current CloudScan production system. We train and evaluate the system on 8 important fields using a dataset of 326,471 invoices. The recurrent neural network and baseline model achieve 0.891 and 0.887 average F1 scores respectively on seen invoice layouts. For the harder task of unseen invoice layouts, the recurrent neural network model outperforms the baseline with 0.840 average F1 compared to 0.788.

##### Abstract (translated by Google)
我们介绍CloudScan;一个需要零配置或预先注释的发票分析系统。与之前的工作相比，CloudScan不依赖发票布局模板，而是学习单一的全球发票模型，这种模式自然会泛化到不可见的发票布局。该模型使用从最终用户提供的反馈自动提取的数据进行训练。这种自动训练数据提取消除了用户精确注释数据的要求。我们描述了一个经常性的神经网络模型，可以捕捉远距离情景并将其与当前CloudScan生产系统对应的基线逻辑回归模型进行比较。我们使用326,471张发票的数据集对8个重要领域的系统进行了培训和评估。经常性的神经网络和基线模型分别在发票布局上获得了0.891和0.887的平均F1分数。对于看不见的发票布局这一难度较大的任务，经常性神经网络模型的平均F1为0.840，而基线为0.788。

##### URL
[https://arxiv.org/abs/1708.07403](https://arxiv.org/abs/1708.07403)

##### PDF
[https://arxiv.org/pdf/1708.07403](https://arxiv.org/pdf/1708.07403)

