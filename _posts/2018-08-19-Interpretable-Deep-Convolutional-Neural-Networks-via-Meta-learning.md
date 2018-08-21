---
layout: post
title: "Interpretable Deep Convolutional Neural Networks via Meta-learning"
date: 2018-08-19 03:20:07
categories: arXiv_AI
tags: arXiv_AI CNN
author: Xuan Liu, Xiaoguang Wang, Stan Matwin
mathjax: true
---

* content
{:toc}

##### Abstract
Model interpretability is a requirement in many applications in which crucial decisions are made by users relying on a model's outputs. The recent movement for "algorithmic fairness" also stipulates explainability, and therefore interpretability of learning models. And yet the most successful contemporary Machine Learning approaches, the Deep Neural Networks, produce models that are highly non-interpretable. We attempt to address this challenge by proposing a technique called CNN-INTE to interpret deep Convolutional Neural Networks (CNN) via meta-learning. In this work, we interpret a specific hidden layer of the deep CNN model on the MNIST image dataset. We use a clustering algorithm in a two-level structure to find the meta-level training data and Random Forest as base learning algorithms to generate the meta-level test data. The interpretation results are displayed visually via diagrams, which clearly indicates how a specific test instance is classified. Our method achieves global interpretation for all the test instances without sacrificing the accuracy obtained by the original deep CNN model. This means our model is faithful to the deep CNN model, which leads to reliable interpretations.

##### Abstract (translated by Google)
模型可解释性是许多应用程序中的一项要求，其中关键决策是由依赖于模型输出的用户做出的。最近的“算法公平”运动也规定了可解释性，因此也规定了学习模型的可解释性。然而，最成功的当代机器学习方法，深度神经网络，产生高度不可解释的模型。我们试图通过提出一种名为CNN-INTE的技术来解决这一挑战，该技术通过元学习解释深度卷积神经网络（CNN）。在这项工作中，我们在MNIST图像数据集上解释深CNN模型的特定隐藏层。我们在两级结构中使用聚类算法来查找元级训练数据，并使用随机森林作为基础学习算法来生成元级别测试数据。解析结果通过图表可视化显示，清楚地表明特定测试实例的分类方式。我们的方法实现了对所有测试实例的全局解释，而不会牺牲原始深度CNN模型所获得的精度。这意味着我们的模型忠实于深度CNN模型，这导致可靠的解释。

##### URL
[http://arxiv.org/abs/1802.00560](http://arxiv.org/abs/1802.00560)

##### PDF
[http://arxiv.org/pdf/1802.00560](http://arxiv.org/pdf/1802.00560)

