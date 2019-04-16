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


##### URL
[https://arxiv.org/abs/1802.00324](https://arxiv.org/abs/1802.00324)

##### PDF
[https://arxiv.org/pdf/1802.00324](https://arxiv.org/pdf/1802.00324)

