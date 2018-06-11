---
layout: post
title: "Revisiting the Importance of Individual Units in CNNs via Ablation"
date: 2018-06-07 20:40:56
categories: arXiv_AI
tags: arXiv_AI CNN Classification Relation Recognition
author: Bolei Zhou, Yiyou Sun, David Bau, Antonio Torralba
mathjax: true
---

* content
{:toc}

##### Abstract
We revisit the importance of the individual units in Convolutional Neural Networks (CNNs) for visual recognition. By conducting unit ablation experiments on CNNs trained on large scale image datasets, we demonstrate that, though ablating any individual unit does not hurt overall classification accuracy, it does lead to significant damage on the accuracy of specific classes. This result shows that an individual unit is specialized to encode information relevant to a subset of classes. We compute the correlation between the accuracy drop under unit ablation and various attributes of an individual unit such as class selectivity and weight L1 norm. We confirm that unit attributes such as class selectivity are a poor predictor for impact on overall accuracy as found previously in recent work \cite{morcos2018importance}. However, our results show that class selectivity along with other attributes are good predictors of the importance of one unit to individual classes. We evaluate the impact of random rotation, batch normalization, and dropout to the importance of units to specific classes. Our results show that units with high selectivity play an important role in network classification power at the individual class level. Understanding and interpreting the behavior of these units is necessary and meaningful.

##### Abstract (translated by Google)
我们重新审视卷积神经网络（CNN）中单个单元对视觉识别的重要性。通过对在大规模图像数据集上训练的CNN进行单位消融实验，我们证明，虽然消除任何单个单位不会损害整体分类准确性，但确实会导致对特定类别准确性的显着损害。该结果表明，单个单元专门用于编码与类的子集相关的信息。我们计算单位消融下的精度下降与单个单位的各种属性（例如类别选择性和权重L1范数）之间的相关性。我们确认单元属性，如类别选择性，对于总体准确度的影响是一个不好的预测因素，正如最近在工作中发现的\ cite {morcos2018importance}。然而，我们的研究结果表明，阶级选择性和其他属性是一个单位对单个阶级重要性的良好预测因子。我们评估随机旋转，批量归一化和丢失对单元对特定类的重要性的影响。我们的结果表明，具有高选择性的单元在个人课堂级别的网络分类能力中起着重要作用。理解和解释这些单位的行为是必要和有意义的。

##### URL
[http://arxiv.org/abs/1806.02891](http://arxiv.org/abs/1806.02891)

##### PDF
[http://arxiv.org/pdf/1806.02891](http://arxiv.org/pdf/1806.02891)

