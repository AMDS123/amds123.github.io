---
layout: post
title: "Collective Anomaly Detection based on Long Short Term Memory Recurrent Neural Network"
date: 2017-03-28 19:04:11
categories: arXiv_CV
tags: arXiv_CV GAN RNN Classification Prediction Detection
author: Loic Bontemps, Van Loi Cao, James McDermott, Nhien-An Le-Khac
mathjax: true
---

* content
{:toc}

##### Abstract
Intrusion detection for computer network systems becomes one of the most critical tasks for network administrators today. It has an important role for organizations, governments and our society due to its valuable resources on computer networks. Traditional misuse detection strategies are unable to detect new and unknown intrusion. Besides, anomaly detection in network security is aim to distinguish between illegal or malicious events and normal behavior of network systems. Anomaly detection can be considered as a classification problem where it builds models of normal network behavior, which it uses to detect new patterns that significantly deviate from the model. Most of the cur- rent research on anomaly detection is based on the learning of normally and anomaly behaviors. They do not take into account the previous, re- cent events to detect the new incoming one. In this paper, we propose a real time collective anomaly detection model based on neural network learning and feature operating. Normally a Long Short Term Memory Recurrent Neural Network (LSTM RNN) is trained only on normal data and it is capable of predicting several time steps ahead of an input. In our approach, a LSTM RNN is trained with normal time series data before performing a live prediction for each time step. Instead of considering each time step separately, the observation of prediction errors from a certain number of time steps is now proposed as a new idea for detecting collective anomalies. The prediction errors from a number of the latest time steps above a threshold will indicate a collective anomaly. The model is built on a time series version of the KDD 1999 dataset. The experiments demonstrate that it is possible to offer reliable and efficient for collective anomaly detection.

##### Abstract (translated by Google)
计算机网络系统的入侵检测成为当今网络管理员最关键的任务之一。由于其在计算机网络上的宝贵资源，它对于组织，政府和我们的社会有着重要的作用。传统的滥用检测策略无法检测到新的和未知的入侵。另外，网络安全中的异常检测是为了区分非法或恶意事件与网络系统的正常行为。异常检测可以被认为是一个分类问题，它建立了正常网络行为的模型，用它来检测显着偏离模型的新模式。目前大多数异常检测研究都是基于正常和异常行为的学习。他们没有考虑到之前发生的新事件。本文提出了一种基于神经网络学习和特征操作的实时集体异常检测模型。通常，长时间记忆递归神经网络（LSTM RNN）仅在正常数据下被训练，并且能够在输入之前预测几个时间步长。在我们的方法中，在对每个时间步进行实时预测之前，对LSTM RNN进行正常时间序列数据的训练。现在提出将某个时间步长的预测误差观测作为检测集体异常的新思路，而不是单独考虑每个时间步骤。来自阈值之上的若干最新时间步骤的预测误差将指示集体异常。该模型建立在KDD 1999数据集的时间序列版本上。实验证明，为集体异常检测提供可靠和有效的可能性。

##### URL
[https://arxiv.org/abs/1703.09752](https://arxiv.org/abs/1703.09752)

##### PDF
[https://arxiv.org/pdf/1703.09752](https://arxiv.org/pdf/1703.09752)

