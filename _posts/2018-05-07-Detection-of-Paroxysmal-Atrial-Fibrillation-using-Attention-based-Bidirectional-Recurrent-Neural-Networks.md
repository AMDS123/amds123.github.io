---
layout: post
title: "Detection of Paroxysmal Atrial Fibrillation using Attention-based Bidirectional Recurrent Neural Networks"
date: 2018-05-07 20:34:17
categories: arXiv_CV
tags: arXiv_CV Attention CNN RNN Deep_Learning Detection
author: Supreeth P. Shashikumar, Amit J. Shah, Gari D. Clifford, Shamim Nemati
mathjax: true
---

* content
{:toc}

##### Abstract
Detection of atrial fibrillation (AF), a type of cardiac arrhythmia, is difficult since many cases of AF are usually clinically silent and undiagnosed. In particular paroxysmal AF is a form of AF that occurs occasionally, and has a higher probability of being undetected. In this work, we present an attention based deep learning framework for detection of paroxysmal AF episodes from a sequence of windows. Time-frequency representation of 30 seconds recording windows, over a 10 minute data segment, are fed sequentially into a deep convolutional neural network for image-based feature extraction, which are then presented to a bidirectional recurrent neural network with an attention layer for AF detection. To demonstrate the effectiveness of the proposed framework for transient AF detection, we use a database of 24 hour Holter Electrocardiogram (ECG) recordings acquired from 2850 patients at the University of Virginia heart station. The algorithm achieves an AUC of 0.94 on the testing set, which exceeds the performance of baseline models. We also demonstrate the cross-domain generalizablity of the approach by adapting the learned model parameters from one recording modality (ECG) to another (photoplethysmogram) with improved AF detection performance. The proposed high accuracy, low false alarm algorithm for detecting paroxysmal AF has potential applications in long-term monitoring using wearable sensors.

##### Abstract (translated by Google)
心房颤动（AF）（一种心律失常）的检测是困难的，因为许多AF患者通常临床上无症状且未诊断。特别是阵发性房颤是偶尔发生的AF的一种形式，并且具有较高的未被检测到的可能性。在这项工作中，我们提出了一种基于注意力的深度学习框架，用于从一系列窗口中检测阵发性房颤的发作。 30秒钟记录窗口的时频表示，超过10分钟的数据段，被顺序地馈送到用于基于图像的特征提取的深度卷积神经网络，然后将其呈现给具有用于AF检测的关注层的双向递归神经网络。为了证明拟议的短暂性AF检测框架的有效性，我们使用从维吉尼亚大学心脏病学站2850名患者获得的24小时Holter心电图（ECG）记录数据库。该算法在测试集上达到0.94的AUC，超过了基线模型的性能。我们还通过将学习的模型参数从一种记录模式（ECG）调整为另一种（光电容积脉搏波图）并具有改进的AF检测性能来证明该方法的跨域可普遍性。所提出的用于检测阵发性房颤的高精度，低误报算法在使用可穿戴传感器的长期监测中具有潜在的应用。

##### URL
[http://arxiv.org/abs/1805.09133](http://arxiv.org/abs/1805.09133)

##### PDF
[http://arxiv.org/pdf/1805.09133](http://arxiv.org/pdf/1805.09133)

