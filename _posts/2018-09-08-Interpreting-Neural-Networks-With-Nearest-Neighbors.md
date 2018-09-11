---
layout: post
title: "Interpreting Neural Networks With Nearest Neighbors"
date: 2018-09-08 18:03:56
categories: arXiv_CL
tags: arXiv_CL Text_Classification Classification Prediction
author: Eric Wallace, Shi Feng, Jordan Boyd-Graber
mathjax: true
---

* content
{:toc}

##### Abstract
Local model interpretation methods explain individual predictions by assigning an importance value to each input feature. This value is often determined by measuring the change in confidence when a feature is removed. However, the confidence of neural networks is not a robust measure of model uncertainty. This issue makes reliably judging the importance of the input features difficult. We address this by changing the test-time behavior of neural networks using Deep k-Nearest Neighbors. Without harming text classification accuracy, this algorithm provides a more robust uncertainty metric which we use to generate feature importance values. The resulting interpretations better align with human perception than baseline methods. Finally, we use our interpretation method to analyze model predictions on dataset annotation artifacts.

##### Abstract (translated by Google)
局部模型解释方法通过为每个输入特征分配重要性值来解释个体预测。通常通过测量移除特征时的置信度变化来确定该值。然而，神经网络的置信度并不是模型不确定性的有力测量。该问题使得可靠地判断输入特征的重要性是困难的。我们通过使用Deep k-Nearest Neighbors改变神经网络的测试时间行为来解决这个问题。在不损害文本分类准确性的情况下，该算法提供了更稳健的不确定性度量，我们使用它来生成特征重要性值。由此产生的解释与基线方法更好地符合人类感知。最后，我们使用我们的解释方法来分析数据集注释工件的模型预测。

##### URL
[http://arxiv.org/abs/1809.02847](http://arxiv.org/abs/1809.02847)

##### PDF
[http://arxiv.org/pdf/1809.02847](http://arxiv.org/pdf/1809.02847)

