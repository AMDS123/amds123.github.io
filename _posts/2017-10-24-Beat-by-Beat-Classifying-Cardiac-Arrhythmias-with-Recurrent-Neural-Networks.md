---
layout: post
title: "Beat by Beat: Classifying Cardiac Arrhythmias with Recurrent Neural Networks"
date: 2017-10-24 09:51:04
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention RNN Classification
author: Patrick Schwab, Gaetano Scebba, Jia Zhang, Marco Delai, Walter Karlen
mathjax: true
---

* content
{:toc}

##### Abstract
With tens of thousands of electrocardiogram (ECG) records processed by mobile cardiac event recorders every day, heart rhythm classification algorithms are an important tool for the continuous monitoring of patients at risk. We utilise an annotated dataset of 12,186 single-lead ECG recordings to build a diverse ensemble of recurrent neural networks (RNNs) that is able to distinguish between normal sinus rhythms, atrial fibrillation, other types of arrhythmia and signals that are too noisy to interpret. In order to ease learning over the temporal dimension, we introduce a novel task formulation that harnesses the natural segmentation of ECG signals into heartbeats to drastically reduce the number of time steps per sequence. Additionally, we extend our RNNs with an attention mechanism that enables us to reason about which heartbeats our RNNs focus on to make their decisions. Through the use of attention, our model maintains a high degree of interpretability, while also achieving state-of-the-art classification performance with an average F1 score of 0.79 on an unseen test set (n=3,658).

##### Abstract (translated by Google)
每天有数万个心电图（ECG）记录由心脏事件记录器处理，心律分类算法是持续监测危险患者的重要工具。我们利用12,186个单导联心电图记录的注释数据集来构建复杂的神经网络（RNN）的多样性集合，能够区分正常的窦性心律，心房颤动，其他类型的心律失常和太嘈杂的解释信号。为了便于在时间维上进行学习，我们引入了一种新的任务公式，将ECG信号的自然分割运用到心跳中，从而大大减少每个序列的时间步数。此外，我们还通过一个注意机制扩展了我们的RNN，使我们能够推断出我们的RNN专注于做出决定的心跳。通过注意力的使用，我们的模型保持了高度的可解释性，同时在一个看不见的测试集（n = 3,658）上获得了平均F1得分为0.79的最新分类性能。

##### URL
[https://arxiv.org/abs/1710.06319](https://arxiv.org/abs/1710.06319)

##### PDF
[https://arxiv.org/pdf/1710.06319](https://arxiv.org/pdf/1710.06319)

