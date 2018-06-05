---
layout: post
title: "DNN Based Speech Enhancement for Unseen Noises Using Monte Carlo Dropout"
date: 2018-06-01 19:21:05
categories: arXiv_SD
tags: arXiv_SD
author: Nazreen P M, A G Ramakrishnan
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we propose the use of dropouts as a Bayesian estimator for increasing the generalizability of a deep neural network (DNN) for speech enhancement. By using Monte Carlo (MC) dropout, we show that the DNN performs better enhancement in unseen noise and SNR conditions. The DNN is trained on speech corrupted with Factory2, M109, Babble, Leopard and Volvo noises at SNRs of 0, 5 and 10 dB and tested on speech with white, pink and factory1 noises. Speech samples are obtained from the TIMIT database and noises from NOISEX-92. In another experiment, we train five DNN models separately on speech corrupted with Factory2, M109, Babble, Leopard and Volvo noises, at 0, 5 and 10 dB SNRs. The model precision (estimated using MC dropout) is used as a proxy for squared error to dynamically select the best of the DNN models based on their performance on each frame of test data.

##### Abstract (translated by Google)
在这项工作中，我们建议使用退出作为贝叶斯估计器来增加用于语音增强的深度神经网络（DNN）的普遍性。通过使用Monte Carlo（MC）辍学，我们证明DNN在看不见的噪声和SNR条件下执行更好的增强。 DNN的语音训练受到Factory2，M109，Babble，Leopard和Volvo噪声的影响，信噪比为0,5和10 dB，并在白色，粉红色和factory1噪声的语音上进行测试。演讲样本来自TIMIT数据库和NOISEX-92的噪音。在另一个实验中，我们分别在Factory2，M109，Babble，Leopard和Volvo噪声损坏的语音上训练5个DNN模型，分别为0,5和10 dB SNR。使用模型精度（使用MC丢失估计）作为平方误差的代理，以根据每个测试数据帧上的性能动态选择最佳的DNN模型。

##### URL
[http://arxiv.org/abs/1806.00516](http://arxiv.org/abs/1806.00516)

##### PDF
[http://arxiv.org/pdf/1806.00516](http://arxiv.org/pdf/1806.00516)

