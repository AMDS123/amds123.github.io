---
layout: post
title: "Using Monte Carlo dropout for non-stationary noise reduction from speech"
date: 2018-08-28 17:46:11
categories: arXiv_SD
tags: arXiv_SD
author: Nazreen P.M., A.G. Ramakrishnan
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we propose the use of dropout as a Bayesian estimator for increasing the generalizability of a deep neural network (DNN) for speech enhancement. By using Monte Carlo (MC) dropout, we show that the DNN performs better enhancement in unseen noise and SNR conditions. The DNN is trained on speech corrupted with Factory2, M109, Babble, Leopard and Volvo noises at SNRs of 0, 5 and 10 dB. Speech samples are obtained from the TIMIT database and noises from NOISEX-92. In another experiment, we train five DNN models separately on speech corrupted with Factory2, M109, Babble, Leopard and Volvo noises, at 0, 5 and 10 dB SNRs. The model precision (estimated using MC dropout) is used as a proxy for squared error to dynamically select the best of the DNN models based on their performance on each frame of test data. We propose an algorithm with a threshold on the model precision to switch between classifier based model selection scheme and model precision based selection scheme. Testing is done on speech corrupted with unseen noises White, Pink and Factory1 and all five seen noises.

##### Abstract (translated by Google)
在这项工作中，我们建议使用丢失作为贝叶斯估计，以增加深度神经网络（DNN）的语音增强的普遍性。通过使用蒙特卡罗（MC）丢失，我们表明DNN在看不见的噪声和SNR条件下表现更好。 DNN经过训练，在SNR为0,5和10 dB时，出现了Factory2，M109，Babble，Leopard和Volvo噪声损坏的语音。语音样本从TIMIT数据库获得，噪声来自NOISEX-92。在另一个实验中，我们分别训练了5个DNN模型，这些模型在使用Factory2，M109，Babble，Leopard和Volvo噪声的语音上分别训练，信噪比为0,5和10 dB。模型精度（使用MC压差估算）用作平方误差的代理，以根据它们在每个测试数据帧上的性能动态选择最佳DNN模型。我们提出了一种具有模型精度阈值的算法，以在基于分类器的模型选择方案和基于模型精度的选择方案之间切换。对看不见的声音白色，粉红色和Factory1以及所有五种看到的噪音进行测试。

##### URL
[http://arxiv.org/abs/1808.09432](http://arxiv.org/abs/1808.09432)

##### PDF
[http://arxiv.org/pdf/1808.09432](http://arxiv.org/pdf/1808.09432)

