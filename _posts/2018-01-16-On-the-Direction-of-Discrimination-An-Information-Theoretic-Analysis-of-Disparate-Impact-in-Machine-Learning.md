---
layout: post
title: "On the Direction of Discrimination: An Information-Theoretic Analysis of Disparate Impact in Machine Learning"
date: 2018-01-16 18:26:56
categories: arXiv_AI
tags: arXiv_AI Optimization Classification Prediction
author: Hao Wang, Berk Ustun, Flavio P. Calmon
mathjax: true
---

* content
{:toc}

##### Abstract
In the context of machine learning, disparate impact refers to a form of systematic discrimination whereby the output distribution of a model depends on the value of a sensitive attribute (e.g., race or gender). In this paper, we present an information-theoretic framework to analyze the disparate impact of a binary classification model. We view the model as a fixed channel, and quantify disparate impact as the divergence in output distributions over two groups. We then aim to find a \textit{correction function} that can be used to perturb the input distributions of each group in order to align their output distributions. We present an optimization problem that can be solved to obtain a correction function that will make the output distributions statistically indistinguishable. We derive closed-form expression for the correction function that can be used to compute it efficiently. We illustrate the use of the correction function for a recidivism prediction application derived from the ProPublica COMPAS dataset.

##### Abstract (translated by Google)
在机器学习的背景下，不同的影响指的是一种系统的歧视，即模型的输出分布取决于敏感属性（例如种族或性别）的价值。在本文中，我们提出了一个信息论框架来分析二元分类模型的不同影响。我们把这个模型看作是一个固定的渠道，并将不同的影响量化为两组产出分布的差异。然后，我们的目标是找到一个可用于扰动每个组的输入分布的校正函数，以对齐它们的输出分布。我们提出了一个可以解决的优化问题，以获得一个校正函数，将使输出分布在统计上难以区分。我们推导出可用于高效计算的校正函数的闭式表达式。我们举例说明了从ProPublica COMPAS数据集导出的累犯预测应用的校正函数的使用。

##### URL
[http://arxiv.org/abs/1801.05398](http://arxiv.org/abs/1801.05398)

##### PDF
[http://arxiv.org/pdf/1801.05398](http://arxiv.org/pdf/1801.05398)

