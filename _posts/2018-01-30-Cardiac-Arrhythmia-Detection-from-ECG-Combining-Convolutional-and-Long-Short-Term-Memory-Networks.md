---
layout: post
title: "Cardiac Arrhythmia Detection from ECG Combining Convolutional and Long Short-Term Memory Networks"
date: 2018-01-30 14:59:57
categories: arXiv_CV
tags: arXiv_CV CNN RNN Classification Prediction Detection Memory_Networks
author: Philip Warrick (1), Masun Nabhan Homsi (2) ((1) PeriGen. Inc., Montreal, Canada, (2) Simon Bolivar University, Caracas, Venezuela)
mathjax: true
---

* content
{:toc}

##### Abstract
Objectives: Atrial fibrillation (AF) is a common heart rhythm disorder associated with deadly and debilitating consequences including heart failure, stroke, poor mental health, reduced quality of life and death. Having an automatic system that diagnoses various types of cardiac arrhythmias would assist cardiologists to initiate appropriate preventive measures and to improve the analysis of cardiac disease. To this end, this paper introduces a new approach to detect and classify automatically cardiac arrhythmias in electrocardiograms (ECG) recordings. Methods: The proposed approach used a combination of Convolution Neural Networks (CNNs) and a sequence of Long Short-Term Memory (LSTM) units, with pooling, dropout and normalization techniques to improve their accuracy. The network predicted a classification at every 18th input sample and we selected the final prediction for classification. Results were cross-validated on the Physionet Challenge 2017 training dataset, which contains 8,528 single lead ECG recordings lasting from 9s to just over 60s. Results: Using the proposed structure and no explicit feature selection, 10-fold stratified cross-validation gave an overall F-measure of 0.83.10-0.015 on the held-out test data (mean-standard deviation over all folds) and 0.80 on the hidden dataset of the Challenge entry server.

##### Abstract (translated by Google)
目标：心房颤动（AF）是一种常见的心律紊乱，与心力衰竭，中风，心理健康欠佳，生活质量和死亡率降低等死亡和衰弱相关。拥有自动诊断各种类型的心律失常的系统将有助于心脏病专家启动适当的预防措施并改善心脏疾病的分析。为此，本文介绍了一种新的方法来检测和分类自动心电图（心电图）记录心律失常。方法：所提出的方法使用卷积神经网络（CNN）和一系列长期短期记忆（LSTM）单元的组合，以提高其准确性。网络每18个输入样本预测一个分类，我们选择最终的分类预测。结果在2017年Physionet Challenge培训数据集上进行了交叉验证，其中包含8,528个单导联心电图记录，持续时间从9s到60多岁。结果：使用所提出的结构并且没有明确的特征选择，10倍分层交叉验证在整个测试数据（所有折叠的平均标准偏差）上给出0.83.10-0.015的整体F-度量，挑战入口服务器的隐藏数据集。

##### URL
[https://arxiv.org/abs/1801.10033](https://arxiv.org/abs/1801.10033)

##### PDF
[https://arxiv.org/pdf/1801.10033](https://arxiv.org/pdf/1801.10033)

