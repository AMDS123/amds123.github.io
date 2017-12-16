---
layout: post
title: "Supervised Learning in Automatic Channel Selection for Epileptic Seizure Detection"
date: 2017-01-31 10:01:45
categories: arXiv_CV
tags: arXiv_CV Classification Detection Relation
author: Nhan Truong, Levin Kuhlmann, Mohammad Reza Bonyadi, Jiawei Yang, Andrew Faulks, Omid Kavehei
mathjax: true
---

* content
{:toc}

##### Abstract
Detecting seizure using brain neuroactivations recorded by intracranial electroencephalogram (iEEG) has been widely used for monitoring, diagnosing, and closed-loop therapy of epileptic patients, however, computational efficiency gains are needed if state-of-the-art methods are to be implemented in implanted devices. We present a novel method for automatic seizure detection based on iEEG data that outperforms current state-of-the-art seizure detection methods in terms of computational efficiency while maintaining the accuracy. The proposed algorithm incorporates an automatic channel selection (ACS) engine as a pre-processing stage to the seizure detection procedure. The ACS engine consists of supervised classifiers which aim to find iEEGchannelswhich contribute the most to a seizure. Seizure detection stage involves feature extraction and classification. Feature extraction is performed in both frequency and time domains where spectral power and correlation between channel pairs are calculated. Random Forest is used in classification of interictal, ictal and early ictal periods of iEEG signals. Seizure detection in this paper is retrospective and patient-specific. iEEG data is accessed via Kaggle, provided by International Epilepsy Electro-physiology Portal. The dataset includes a training set of 6.5 hours of interictal data and 41 minin ictal data and a test set of 9.14 hours. Compared to the state-of-the-art on the same dataset, we achieve 49.4% increase in computational efficiency and 400 mins better in average for detection delay. The proposed model is able to detect a seizure onset at 91.95% sensitivity and 94.05% specificity with a mean detection delay of 2.77 s. The area under the curve (AUC) is 96.44%, that is comparable to the current state-of-the-art with AUC of 96.29%.

##### Abstract (translated by Google)
使用颅内脑电图（iEEG）记录的脑神经激活检测癫痫发作已被广泛用于癫痫患者的监测，诊断和闭环治疗，然而，如果要实施最先进的方法，则需要提高计算效率在植入装置中。我们提出了一种基于iEEG数据的自动癫痫发现检测新方法，该方法在保持准确性的同时，在计算效率方面优于当前最先进的癫痫发作检测方法。所提出的算法结合了自动信道选择（ACS）引擎作为缉获检测程序的预处理阶段。 ACS引擎由有监督的分类器组成，其目的是发现对癫痫发作贡献最大的iEEG信道。发作检测阶段涉及特征提取和分类。在计算频道功率和频道对之间的相关性的频域和时域中执行特征提取。随机森林用于iEEG信号的发作间期，发作期和早期发作期的分类。本文中的癫痫发作是回顾性和患者特异性的。国际癫痫电生理门户网站提供的KEGLE可以访问iEEG数据。数据集包括6.5小时的发作间数据和41小时的发作数据以及9.14小时的测试组。与同一数据集的最新技术相比，计算效率提高了49.4％，平均检测延迟提高了400分钟。该模型能够检测到91.95％的敏感性和94.05％的特异性，平均检测延迟为2.77s。曲线下面积（AUC）为96.44％，与当前AUC为96.29％的现状相当。

##### URL
[https://arxiv.org/abs/1701.08968](https://arxiv.org/abs/1701.08968)

##### PDF
[https://arxiv.org/pdf/1701.08968](https://arxiv.org/pdf/1701.08968)

