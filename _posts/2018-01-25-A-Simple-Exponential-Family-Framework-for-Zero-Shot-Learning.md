---
layout: post
title: "A Simple Exponential Family Framework for Zero-Shot Learning"
date: 2018-01-25 05:37:04
categories: arXiv_CV
tags: arXiv_CV Embedding
author: Vinay Kumar Verma, Piyush Rai
mathjax: true
---

* content
{:toc}

##### Abstract
We present a simple generative framework for learning to predict previously unseen classes, based on estimating class-attribute-gated class-conditional distributions. We model each class-conditional distribution as an exponential family distribution and the parameters of the distribution of each seen/unseen class are defined as functions of the respective observed class attributes. These functions can be learned using only the seen class data and can be used to predict the parameters of the class-conditional distribution of each unseen class. Unlike most existing methods for zero-shot learning that represent classes as fixed embeddings in some vector space, our generative model naturally represents each class as a probability distribution. It is simple to implement and also allows leveraging additional unlabeled data from unseen classes to improve the estimates of their class-conditional distributions using transductive/semi-supervised learning. Moreover, it extends seamlessly to few-shot learning by easily updating these distributions when provided with a small number of additional labelled examples from unseen classes. Through a comprehensive set of experiments on several benchmark data sets, we demonstrate the efficacy of our framework.

##### Abstract (translated by Google)
我们提出了一个简单的生成框架来学习预测以前看不见的类，基于估计类属性门控类的条件分布。我们将每个类别条件分布建模为指数族分布，并且将每个看到/看不见的类的分布参数定义为各个观察类别属性的函数。这些函数可以仅使用所看到的类数据来学习，并且可以用来预测每个看不见的类的类 - 条件分布的参数。与大多数现有零点学习方法不同，它们将类表示为某些向量空间中的固定嵌入，我们的生成模型自然地将每个类别表示为概率分布。实施起来很简单，并且还允许利用来自看不见的类别的额外未标记数据来改进使用直推/半监督学习的类别条件分布的估计。此外，它可以无缝地扩展到少数学习，只要提供少量来自不可见类别的附加标记示例，便可轻松更新这些分布。通过对几个基准数据集的全面实验，我们展示了我们框架的功效。

##### URL
[http://arxiv.org/abs/1707.08040](http://arxiv.org/abs/1707.08040)

##### PDF
[http://arxiv.org/pdf/1707.08040](http://arxiv.org/pdf/1707.08040)

