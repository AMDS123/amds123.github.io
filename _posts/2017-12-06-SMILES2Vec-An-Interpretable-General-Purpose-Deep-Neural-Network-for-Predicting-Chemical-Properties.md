---
layout: post
title: "SMILES2Vec: An Interpretable General-Purpose Deep Neural Network for Predicting Chemical Properties"
date: 2017-12-06 04:29:28
categories: arXiv_CL
tags: arXiv_CL RNN Deep_Learning
author: Garrett B. Goh, Nathan O. Hodas, Charles Siegel, Abhinav Vishnu
mathjax: true
---

* content
{:toc}

##### Abstract
Chemical databases store information in text representations, and the SMILES format is a universal standard used in many cheminformatics software. Encoded in each SMILES string is structural information that can be used to predict complex chemical properties. In this work, we develop SMILES2Vec, a deep RNN that automatically learns features from SMILES strings to predict chemical properties, without the need for additional explicit chemical information, or the "grammar" of how SMILES encode structural data. Using Bayesian optimization methods to tune the network architecture, we show that an optimized SMILES2Vec model can serve as a general-purpose neural network for learning a range of distinct chemical properties including toxicity, activity, solubility and solvation energy, while outperforming contemporary MLP networks that uses engineered features. Furthermore, we demonstrate proof-of-concept of interpretability by developing an explanation mask that localizes on the most important characters used in making a prediction. When tested on the solubility dataset, this localization identifies specific parts of a chemical that is consistent with established first-principles knowledge of solubility with an accuracy of 88%, demonstrating that neural networks can learn technically accurate chemical concepts. The fact that SMILES2Vec validates established chemical facts, while providing state-of-the-art accuracy, makes it a potential tool for widespread adoption of interpretable deep learning by the chemistry community.

##### Abstract (translated by Google)
化学数据库以文本表示方式存储信息，SMILES格式是许多化学信息学软件中使用的通用标准。在每个SMILES字符串中编码是可用于预测复杂化学特性的结构信息。在这项工作中，我们开发了SMILES2Vec，这是一种深度RNN，可以自动从SMILES字符串中学习特征来预测化学性质，而不需要额外的明确的化学信息，或SMILES如何编码结构数据的“语法”。使用贝叶斯优化方法调整网络架构，我们展示了一个优化的SMILES2Vec模型可以作为一个通用的神经网络学习一系列不同的化学性质，包括毒性，活性，溶解度和溶剂化能量，同时超越当代的MLP网络使用工程功能。此外，我们通过开发解释掩码来证明解释性的概念，该解释掩码定位用于进行预测的最重要的字符。当在溶解度数据集上进行测试时，这种定位标识了化学物质的特定部分，与已知的溶解度第一性原理知识一致，精确度为88％，证明了神经网络可以学习技术上准确的化学概念。 SMILES2Vec验证既定的化学事实，同时提供最先进的准确性，使其成为化学界广泛采用可解释的深度学习的潜在工具。

##### URL
[http://arxiv.org/abs/1712.02034](http://arxiv.org/abs/1712.02034)

##### PDF
[http://arxiv.org/pdf/1712.02034](http://arxiv.org/pdf/1712.02034)

