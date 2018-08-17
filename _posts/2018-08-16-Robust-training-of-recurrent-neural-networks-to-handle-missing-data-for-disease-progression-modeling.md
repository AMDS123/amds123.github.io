---
layout: post
title: "Robust training of recurrent neural networks to handle missing data for disease progression modeling"
date: 2018-08-16 14:09:22
categories: arXiv_CV
tags: arXiv_CV Image_Classification RNN Classification Prediction
author: Mostafa Mehdipour Ghazi, Mads Nielsen, Akshay Pai, M. Jorge Cardoso, Marc Modat, Sebastien Ourselin, Lauge S&#xf8;rensen
mathjax: true
---

* content
{:toc}

##### Abstract
Disease progression modeling (DPM) using longitudinal data is a challenging task in machine learning for healthcare that can provide clinicians with better tools for diagnosis and monitoring of disease. Existing DPM algorithms neglect temporal dependencies among measurements and make parametric assumptions about biomarker trajectories. In addition, they do not model multiple biomarkers jointly and need to align subjects' trajectories. In this paper, recurrent neural networks (RNNs) are utilized to address these issues. However, in many cases, longitudinal cohorts contain incomplete data, which hinders the application of standard RNNs and requires a pre-processing step such as imputation of the missing values. We, therefore, propose a generalized training rule for the most widely used RNN architecture, long short-term memory (LSTM) networks, that can handle missing values in both target and predictor variables. This algorithm is applied for modeling the progression of Alzheimer's disease (AD) using magnetic resonance imaging (MRI) biomarkers. The results show that the proposed LSTM algorithm achieves a lower mean absolute error for prediction of measurements across all considered MRI biomarkers compared to using standard LSTM networks with data imputation or using a regression-based DPM method. Moreover, applying linear discriminant analysis to the biomarkers' values predicted by the proposed algorithm results in a larger area under the receiver operating characteristic curve (AUC) for clinical diagnosis of AD compared to the same alternatives, and the AUC is comparable to state-of-the-art AUCs from a recent cross-sectional medical image classification challenge. This paper shows that built-in handling of missing values in LSTM network training paves the way for application of RNNs in disease progression modeling.

##### Abstract (translated by Google)
使用纵向数据的疾病进展建模（DPM）是用于医疗保健的机器学习中的具有挑战性的任务，其可以为临床医生提供用于诊断和监测疾病的更好工具。现有的DPM算法忽略了测量之间的时间依赖性并且做出关于生物标记轨迹的参数假设。此外，他们不会联合模拟多个生物标志物，需要调整受试者的轨迹。在本文中，利用递归神经网络（RNN）来解决这些问题。然而，在许多情况下，纵向群组包含不完整的数据，这阻碍了标准RNN的应用，并且需要预处理步骤，例如插补缺失值。因此，我们为最广泛使用的RNN架构 - 长短期记忆（LSTM）网络提出了一个通用的训练规则，它可以处理目标和预测变量中的缺失值。该算法用于使用磁共振成像（MRI）生物标记物对阿尔茨海默病（AD）的进展进行建模。结果表明，与使用具有数据插补的标准LSTM网络或使用基于回归的DPM方法相比，所提出的LSTM算法实现了用于预测所有考虑的MRI生物标记物的测量的较低的平均绝对误差。此外，将线性判别分析应用于由所提出的算法预测的生物标记物值导致在AD的临床诊断的接受者操作特征曲线（AUC）下与相同的替代物相比更大的面积，并且AUC与状态相当。来自最近的横截面医学图像分类挑战的最新AUC。本文表明，LSTM网络训练中缺失值的内置处理为RNN在疾病进展建模中的应用铺平了道路。

##### URL
[http://arxiv.org/abs/1808.05500](http://arxiv.org/abs/1808.05500)

##### PDF
[http://arxiv.org/pdf/1808.05500](http://arxiv.org/pdf/1808.05500)

