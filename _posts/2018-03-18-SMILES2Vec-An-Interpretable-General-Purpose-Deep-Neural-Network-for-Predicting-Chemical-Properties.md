---
layout: post
title: "SMILES2Vec: An Interpretable General-Purpose Deep Neural Network for Predicting Chemical Properties"
date: 2018-03-18 13:50:32
categories: arXiv_AI
tags: arXiv_AI Knowledge Optimization RNN Prediction
author: Garrett B. Goh, Nathan O. Hodas, Charles Siegel, Abhinav Vishnu
mathjax: true
---

* content
{:toc}

##### Abstract
Chemical databases store information in text representations, and the SMILES format is a universal standard used in many cheminformatics software. Encoded in each SMILES string is structural information that can be used to predict complex chemical properties. In this work, we develop SMILES2vec, a deep RNN that automatically learns features from SMILES to predict chemical properties, without the need for additional explicit feature engineering. Using Bayesian optimization methods to tune the network architecture, we show that an optimized SMILES2vec model can serve as a general-purpose neural network for predicting distinct chemical properties including toxicity, activity, solubility and solvation energy, while also outperforming contemporary MLP neural networks that uses engineered features. Furthermore, we demonstrate proof-of-concept of interpretability by developing an explanation mask that localizes on the most important characters used in making a prediction. When tested on the solubility dataset, it identified specific parts of a chemical that is consistent with established first-principles knowledge with an accuracy of 88%. Our work demonstrates that neural networks can learn technically accurate chemical concept and provide state-of-the-art accuracy, making interpretable deep neural networks a useful tool of relevance to the chemical industry.

##### Abstract (translated by Google)
化学数据库以文本表示形式存储信息，SMILES格式是许多化学信息学软件中使用的通用标准。在每个SMILES字符串中编码的结构信息可用于预测复杂的化学特性。在这项工作中，我们开发了SMILES2vec，一种深度RNN，可以自动学习SMILES的特征来预测化学特性，而无需额外的显式特征工程。使用贝叶斯优化方法来调整网络架构，我们表明优化的SMILES2vec模型可以作为通用神经网络用于预测不同的化学特性，包括毒性，活性，溶解度和溶剂化能量，同时也优于使用当代MLP神经网络工程特征。此外，我们通过开发一个解释掩码来演示可解释性的概念，该解释掩码定位于用于进行预测的最重要的字符。在溶解度数据集上进行测试时，它确定了化学品的特定部分，这些部分与已建立的第一原理知识一致，准确度为88％。我们的工作表明神经网络可以学习技术上准确的化学概念并提供最先进的精确度，使可解释的深度神经网络成为与化学工业相关的有用工具。

##### URL
[http://arxiv.org/abs/1712.02034](http://arxiv.org/abs/1712.02034)

##### PDF
[http://arxiv.org/pdf/1712.02034](http://arxiv.org/pdf/1712.02034)

