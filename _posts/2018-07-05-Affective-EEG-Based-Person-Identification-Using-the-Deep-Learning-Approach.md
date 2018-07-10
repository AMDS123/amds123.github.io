---
layout: post
title: "Affective EEG-Based Person Identification Using the Deep Learning Approach"
date: 2018-07-05 22:43:01
categories: arXiv_CV
tags: arXiv_CV CNN RNN Deep_Learning Recognition
author: Theerawit Wilaiprasitporn, Apiwat Ditthapron, Karis Matchaparn, Tanaboon Tongbuasirilai, Nannapas Banluesombatkul, Ekapol Chuangsuwanich
mathjax: true
---

* content
{:toc}

##### Abstract
There are several reports available on affective electroencephalography-based personal identification (affective EEG-based PI), one of which uses a small dataset and another reaching less than 90\% of the mean correct recognition rate \emph{CRR},. Thus, the aim of this paper is to improve and evaluate the performance of affective EEG-based PI using a deep learning approach. The state-of-the-art EEG dataset DEAP was used as the standard for affective recognition. Thirty-two healthy participants participated in the experiment. They were asked to watch affective elicited music videos and score subjective ratings for forty video clips during the EEG measurement. An EEG amplifier with thirty-two electrodes was used to record affective EEG measurements from the participants. To identify personal EEG, a cascade of deep learning architectures was proposed, using a combination of Convolutional Neural Networks (CNNs) and Recurrent Neural Networks (RNNs). CNNs are used to handle the spatial information from the EEG while RNNs extract the temporal information. There has been a cascade of CNNs, with recurrent models known as Long Short-Term Memory (CNN-LSTM) and Gate Recurrent Unit (CNN-GRU) for comparison. Experimental results indicate that CNN-GRU and CNN-LSTM can deal with an EEG (4--40 Hz) rom different affective states and reach up to 99.90--100\% mean \emph{CRR}. On the other hand, a traditional machine learning approach such as a support vector machine (SVM) using power spectral density (PSD) as a feature does not reach 50\% mean \emph{CRR}. To reduce the number of EEG electrodes from thirty-two to five for more practical application, $F_{3}$, $F_{4}$, $F_{z}$, $F_{7}$ and $F_{8}$ were found to be the best five electrodes for application in similar scenarios to those in this study. CNN-GRU and CNN-LSTM reached up to 99.17\% and 98.23\% mean \emph{CRR}, respectively.

##### Abstract (translated by Google)
有几个关于基于情感脑电图的个人识别（基于情感EEG的PI）的报告，其中一个使用小数据集，另一个达到平均正确识别率\ emph {CRR}的不到90％。因此，本文的目的是使用深度学习方法改进和评估基于情感EEG的PI的表现。最先进的脑电数据集DEAP被用作情感识别的标准。 32名健康参与者参加了实验。在EEG测量期间，他们被要求观看情感引发的音乐视频并对40个视频剪辑进行主观评分。具有三十二个电极的EEG放大器用于记录来自参与者的情感EEG测量值。为了识别个人脑电图，使用卷积神经网络（CNN）和递归神经网络（RNN）的组合提出了一系列深度学习架构。 CNN用于处理来自EEG的空间信息，而RNN提取时间信息。存在级联的CNN，具有称为长短期存储器（CNN-LSTM）和门复用单元（CNN-GRU）的循环模型用于比较。实验结果表明，CNN-GRU和CNN-LSTM可以处理不同情感状态的EEG（4--40 Hz），达到99.90-100％\ mean \ emph {CRR}。另一方面，传统的机器学习方法，例如使用功率谱密度（PSD）作为特征的支持向量机（SVM），达不到50％的平均值\ emph {CRR}。为了更实际的应用，将EEG电极的数量从32个减少到5个，$ F_ {3} $，$ F_ {4} $，$ F_ {z} $，$ F_ {7} $和$ F_ {8 } $被发现是与本研究中类似场景中应用的最佳五电极。 CNN-GRU和CNN-LSTM分别达到99.17 \％和98.23 \％均值\ emph {CRR}。

##### URL
[http://arxiv.org/abs/1807.03147](http://arxiv.org/abs/1807.03147)

##### PDF
[http://arxiv.org/pdf/1807.03147](http://arxiv.org/pdf/1807.03147)

