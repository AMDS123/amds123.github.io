---
layout: post
title: "End-to-end learning potentials for structured attribute prediction"
date: 2017-08-06 13:56:31
categories: arXiv_CV
tags: arXiv_CV Sparse Inference Prediction Relation
author: Kota Yamaguchi, Takayuki Okatani, Takayuki Umeda, Kazuhiko Murasaki, Kyoko Sudo
mathjax: true
---

* content
{:toc}

##### Abstract
We present a structured inference approach in deep neural networks for multiple attribute prediction. In attribute prediction, a common approach is to learn independent classifiers on top of a good feature representation. However, such classifiers assume conditional independence on features and do not explicitly consider the dependency between attributes in the inference process. We propose to formulate attribute prediction in terms of marginal inference in the conditional random field. We model potential functions by deep neural networks and apply the sum-product algorithm to solve for the approximate marginal distribution in feed-forward networks. Our message passing layer implements sparse pairwise potentials by a softplus-linear function that is equivalent to a higher-order classifier, and learns all the model parameters by end-to-end back propagation. The experimental results using SUN attributes and CelebA datasets suggest that the structured inference improves the attribute prediction performance, and possibly uncovers the hidden relationship between attributes.

##### Abstract (translated by Google)
我们在深度神经网络中提出了一种结构化的推理方法来进行多属性预测。在属性预测中，常用的方法是在良好的特征表示之上学习独立的分类器。然而，这样的分类器假定条件对特征的独立性，并没有明确考虑推理过程中属性之间的依赖关系。我们提出用条件随机场中的边际推理来表述属性预测。我们通过深度神经网络对势函数进行建模，并应用和积算法求解前馈网络中的近似边际分布。我们的消息传递层通过相当于高阶分类器的softplus-linear函数实现稀疏的成对电势，并通过端到端的反向传播学习所有的模型参数。使用SUN属性和CelebA数据集的实验结果表明，结构化推理提高了属性预测的性能，并可能揭示属性之间的隐藏关系。

##### URL
[https://arxiv.org/abs/1708.01892](https://arxiv.org/abs/1708.01892)

##### PDF
[https://arxiv.org/pdf/1708.01892](https://arxiv.org/pdf/1708.01892)

