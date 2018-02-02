---
layout: post
title: "One-class Collective Anomaly Detection based on Long Short-Term Memory Recurrent Neural Networks"
date: 2018-01-31 10:38:07
categories: arXiv_CV
tags: arXiv_CV GAN RNN Classification Prediction Detection
author: Nga Nguyen Thi, Van Loi Cao, Nhien-An Le-Khac
mathjax: true
---

* content
{:toc}

##### Abstract
Intrusion detection for computer network systems has been becoming one of the most critical tasks for network administrators today. It has an important role for organizations, governments and our society due to the valuable resources hosted on computer networks. Traditional misuse detection strategies are unable to detect new and unknown intrusion types. In contrast, anomaly detection in network security aims to distinguish between illegal or malicious events and normal behavior of network systems. Anomaly detection can be considered as a classification problem where it builds models of normal network behavior, of which it uses to detect new patterns that significantly deviate from the model. Most of the current approaches on anomaly detection is based on the learning of normal behavior and anomalous actions. They do not include memory that is they do not take into account previous events classify new ones. In this paper, we propose a one class collective anomaly detection model based on neural network learning. Normally a Long Short Term Memory Recurrent Neural Network (LSTM RNN) is trained only on normal data, and it is capable of predicting several time steps ahead of an input. In our approach, a LSTM RNN is trained on normal time series data before performing a prediction for each time step. Instead of considering each time-step separately, the observation of prediction errors from a certain number of time-steps is now proposed as a new idea for detecting collective anomalies. The prediction errors of a certain number of the latest time-steps above a threshold will indicate a collective anomaly. The model is evaluated on a time series version of the KDD 1999 dataset. The experiments demonstrate that the proposed model is capable to detect collective anomaly efficiently

##### Abstract (translated by Google)
计算机网络系统的入侵检测已经成为当今网络管理员最关键的任务之一。由于计算机网络上有宝贵的资源，它对组织，政府和社会有着重要的作用。传统的滥用检测策略无法检测到新的和未知的入侵类型。而网络安全中的异常检测则是为了区分非法或恶意事件与网络系统的正常行为。异常检测可以被认为是一个分类问题，它建立了正常网络行为的模型，用它来检测显着偏离模型的新模式。目前大多数异常检测方法是基于对正常行为和异常行为的学习。他们不包括记忆，他们没有考虑到以前的事件分类新的。本文提出了一种基于神经网络学习的一类集体异常检测模型。通常情况下，长时间记忆递归神经网络（LSTM RNN）仅在正常数据下被训练，并且能够预测输入之前的几个时间步长。在我们的方法中，在对每个时间步进行预测之前，对正常时间序列数据训练LSTM RNN。现在提出将观测到的某些时间步长的预测误差作为检测集体异常的新思路，而不是单独考虑每个时间步骤。一定数量的最新时间步骤的预测误差将表示一个集体异常。该模型是在KDD 1999数据集的时间序列版本上进行评估的。实验证明，该模型能够有效检测出集体异常

##### URL
[https://arxiv.org/abs/1802.00324](https://arxiv.org/abs/1802.00324)

##### PDF
[https://arxiv.org/pdf/1802.00324](https://arxiv.org/pdf/1802.00324)

