---
layout: post
title: "On-line Human Gait Stability Prediction using LSTMs for the fusion of Deep-based Pose Estimation and LRF-based Augmented Gait State Estimation in an Intelligent Robotic Rollator"
date: 2018-12-01 19:50:56
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation RNN Deep_Learning Prediction
author: Georgia Chalvatzaki, Petros Koutras, Jack Hadfield, Xanthi S. Papageorgiou, Costas S. Tzafestas, Petros Maragos
mathjax: true
---

* content
{:toc}

##### Abstract
In this work we present a novel Long Short Term Memory (LSTM) based on-line human gait stability prediction framework for the elderly users of an intelligent robotic rollator, using only non-wearable sensors, fusing multimodal RGB-D and Laser Range Finder (LRF) data. A deep learning (DL) based approach is used for the upper body pose estimation. The detected pose is used for estimating the Center of Mass (CoM) of the body using Unscented Kalman Filter (UKF). An Augmented Gait State Estimation framework exploits the LRF data to estimate the legs' positions and the respective gait phase. These estimates are the inputs of an encoder-decoder sequence to sequence model which predicts the gait stability state as Safe or Fall Risk walking. It is validated with data from real patients, by exploring different network architectures, hyperparameter settings and by comparing the proposed method with other baselines. The presented LSTM-based human gait stability predictor is shown to provide robust predictions of the human stability state, and thus has the potential to be integrated into a general user-adaptive control architecture as a fall-risk alarm.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.00252](http://arxiv.org/abs/1812.00252)

##### PDF
[http://arxiv.org/pdf/1812.00252](http://arxiv.org/pdf/1812.00252)

