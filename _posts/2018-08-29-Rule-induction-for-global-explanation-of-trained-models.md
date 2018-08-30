---
layout: post
title: "Rule induction for global explanation of trained models"
date: 2018-08-29 12:02:11
categories: arXiv_CL
tags: arXiv_CL Text_Classification Classification Prediction Relation
author: Madhumita Sushil, Simon &#x160;uster, Walter Daelemans
mathjax: true
---

* content
{:toc}

##### Abstract
Understanding the behavior of a trained network and finding explanations for its outputs is important for improving the network's performance and generalization ability, and for ensuring trust in automated systems. Several approaches have previously been proposed to identify and visualize the most important features by analyzing a trained network. However, the relations between different features and classes are lost in most cases. We propose a technique to induce sets of if-then-else rules that capture these relations to globally explain the predictions of a network. We first calculate the importance of the features in the trained network. We then weigh the original inputs with these feature importance scores, simplify the transformed input space, and finally fit a rule induction model to explain the model predictions. We find that the output rule-sets can explain the predictions of a neural network trained for 4-class text classification from the 20 newsgroups dataset to a macro-averaged F-score of 0.80. We make the code available at https://github.com/clips/interpret_with_rules.

##### Abstract (translated by Google)
了解受过训练的网络的行为并找到其输出的解释对于提高网络的性能和泛化能力以及确保对自动化系统的信任非常重要。先前已经提出了几种方法来通过分析训练的网络来识别和可视化最重要的特征。但是，在大多数情况下，不同特征和类之间的关系都会丢失。我们提出了一种技术来诱导if-then-else规则集，捕获这些关系以全局解释网络的预测。我们首先计算训练网络中特征的重要性。然后，我们将原始输入与这些特征重要性分数进行权衡，简化变换后的输入空间，最后拟合规则归纳模型来解释模型预测。我们发现输出规则集可以解释从20个新闻组数据集训练为4级文本分类的神经网络的预测到0.80的宏观平均F分数。我们在https://github.com/clips/interpret_with_rules上提供代码。

##### URL
[http://arxiv.org/abs/1808.09744](http://arxiv.org/abs/1808.09744)

##### PDF
[http://arxiv.org/pdf/1808.09744](http://arxiv.org/pdf/1808.09744)

