---
layout: post
title: "Right for the Right Reason: Training Agnostic Networks"
date: 2018-06-16 21:09:40
categories: arXiv_CV
tags: arXiv_CV Adversarial Prediction Relation
author: Sen Jia, Thomas Lansdall-Welfare, Nello Cristianini
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the problem of a neural network being requested to classify images (or other inputs) without making implicit use of a "protected concept", that is a concept that should not play any role in the decision of the network. Typically these concepts include information such as gender or race, or other contextual information such as image backgrounds that might be implicitly reflected in unknown correlations with other variables, making it insufficient to simply remove them from the input features. In other words, making accurate predictions is not good enough if those predictions rely on information that should not be used: predictive performance is not the only important metric for learning systems. We apply a method developed in the context of domain adaptation to address this problem of "being right for the right reason", where we request a classifier to make a decision in a way that is entirely 'agnostic' to a given protected concept (e.g. gender, race, background etc.), even if this could be implicitly reflected in other attributes via unknown correlations. After defining the concept of an 'agnostic model', we demonstrate how the Domain-Adversarial Neural Network can remove unwanted information from a model using a gradient reversal layer.

##### Abstract (translated by Google)
我们考虑要求神经网络对图像（或其他输入）进行分类而不隐含使用“受保护的概念”的问题，这是一个不应该在网络决策中起任何作用的概念。通常情况下，这些概念包括诸如性别或种族等信息或其他背景信息（如图像背景），这些信息可能隐含地反映在与其他变量的未知相关性中，使其不足以将其从输入要素中简单移除。换句话说，如果这些预测依赖于不应该使用的信息，那么做出准确的预测还不够好：预测性能并不是学习系统的唯一重要指标。我们运用在领域适应的背景下开发的方法来解决“为正确理由正确”的问题，我们要求分类器以对给定的受保护概念完全“不可知”的方式作出决定（例如性别，种族，背景等），即使这可能通过未知的相关性隐含地反映在其他属性中。在定义了“不可知论模型”的概念之后，我们演示了领域对抗神经网络如何使用梯度反转层从模型中去除不需要的信息。

##### URL
[http://arxiv.org/abs/1806.06296](http://arxiv.org/abs/1806.06296)

##### PDF
[http://arxiv.org/pdf/1806.06296](http://arxiv.org/pdf/1806.06296)

