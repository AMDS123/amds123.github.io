---
layout: post
title: "A Generalised Seizure Prediction with Convolutional Neural Networks for Intracranial and Scalp Electroencephalogram Data Analysis"
date: 2017-12-06 11:48:22
categories: arXiv_CV
tags: arXiv_CV Attention CNN Classification Prediction
author: Nhan Duy Truong, Anh Duy Nguyen, Levin Kuhlmann, Mohammad Reza Bonyadi, Jiawei Yang, Omid Kavehei
mathjax: true
---

* content
{:toc}

##### Abstract
Seizure prediction has attracted a growing attention as one of the most challenging predictive data analysis efforts in order to improve the life of patients living with drug-resistant epilepsy and tonic seizures. Many outstanding works have been reporting great results in providing a sensible indirect (warning systems) or direct (interactive neural-stimulation) control over refractory seizures, some of which achieved high performance. However, many works put heavily handcraft feature extraction and/or carefully tailored feature engineering to each patient to achieve very high sensitivity and low false prediction rate for a particular dataset. This limits the benefit of their approaches if a different dataset is used. In this paper we apply Convolutional Neural Networks (CNNs) on different intracranial and scalp electroencephalogram (EEG) datasets and proposed a generalized retrospective and patient-specific seizure prediction method. We use Short-Time Fourier Transform (STFT) on 30-second EEG windows with 50% overlapping to extract information in both frequency and time domains. A standardization step is then applied on STFT components across the whole frequency range to prevent high frequencies features being influenced by those at lower frequencies. A convolutional neural network model is used for both feature extraction and classification to separate preictal segments from interictal ones. The proposed approach achieves sensitivity of 81.4%, 81.2%, 82.3% and false prediction rate (FPR) of 0.06/h, 0.16/h, 0.22/h on Freiburg Hospital intracranial EEG (iEEG) dataset, Children's Hospital of Boston-MIT scalp EEG (sEEG) dataset, and Kaggle American Epilepsy Society Seizure Prediction Challenge's dataset, respectively. Our prediction method is also statistically better than an unspecific random predictor for most of patients in all three datasets.

##### Abstract (translated by Google)
作为最具挑战性的预测性数据分析工作之一，癫痫发作预测越来越受到关注，以改善患有耐药性癫痫和强直性癫痫发作的患者的生活。许多优秀的作品已经在对难治性癫痫发作提供合理的间接（预警系统）或直接（交互式神经刺激）控制方面报告了巨大的成果，其中一些获得了高性能。然而，许多作品对每个患者进行了大量手工特征提取和/或精心设计的特征工程，以针对特定数据集实现非常高的灵敏度和低的错误预测率。如果使用不同的数据集，这限制了他们的方法的好处。本文将卷积神经网络（CNNs）应用于不同的颅内和头皮脑电图（EEG）数据集，并提出了一种广义的回顾性和患者特异性癫痫发作预测方法。我们在30秒的EEG窗口上使用短时傅立叶变换（STFT），重叠率为50％，以提取频域和时域的信息。然后在整个频率范围内对STFT组件进行标准化步骤，以防止高频特征受到较低频率特征的影响。卷积神经网络模型被用于特征提取和分类，以将发作段与发作段分开。该方法在弗莱堡医院颅内脑电图（iEEG）数据集，波士顿儿童医院麻省理工学院头皮病患者的灵敏度分别达到了81.4％，81.2％，82.3％和0.06 / h，0.16 / h，0.22 / h的误报率EEG（sEEG）数据集和Kaggle美国癫痫协会癫痫发作预测挑战的数据集。对于所有三个数据集中的大多数患者，我们的预测方法在统计学上也优于非特异性随机预测因子。

##### URL
[http://arxiv.org/abs/1707.01976](http://arxiv.org/abs/1707.01976)

##### PDF
[http://arxiv.org/pdf/1707.01976](http://arxiv.org/pdf/1707.01976)

