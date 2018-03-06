---
layout: post
title: "Egocentric Basketball Motion Planning from a Single First-Person Image"
date: 2018-03-04 20:12:58
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN CNN RNN Deep_Learning Memory_Networks
author: Gedas Bertasius, Aaron Chan, Jianbo Shi
mathjax: true
---

* content
{:toc}

##### Abstract
We present a model that uses a single first-person image to generate an egocentric basketball motion sequence in the form of a 12D camera configuration trajectory, which encodes a player's 3D location and 3D head orientation throughout the sequence. To do this, we first introduce a future convolutional neural network (CNN) that predicts an initial sequence of 12D camera configurations, aiming to capture how real players move during a one-on-one basketball game. We also introduce a goal verifier network, which is trained to verify that a given camera configuration is consistent with the final goals of real one-on-one basketball players. Next, we propose an inverse synthesis procedure to synthesize a refined sequence of 12D camera configurations that (1) sufficiently matches the initial configurations predicted by the future CNN, while (2) maximizing the output of the goal verifier network. Finally, by following the trajectory resulting from the refined camera configuration sequence, we obtain the complete 12D motion sequence. 
 Our model generates realistic basketball motion sequences that capture the goals of real players, outperforming standard deep learning approaches such as recurrent neural networks (RNNs), long short-term memory networks (LSTMs), and generative adversarial networks (GANs).

##### Abstract (translated by Google)
我们提出了一种模型，该模型使用单个第一人称图像以12D相机配置轨迹的形式生成以自我为中心的篮球运动序列，其在整个序列中编码玩家的3D位置和3D头部方向。为此，我们首先介绍未来的卷积神经网络（CNN），预测12D相机配置的初始序列，旨在捕捉真实玩家在一对一篮球比赛中的移动方式。我们还引入了一个目标验证者网络，该网络经过训练以验证给定的摄像头配置是否与真正的一对一篮球运动员的最终目标一致。接下来，我们提出一个逆合成过程来合成12D相机配置的改进序列，其（1）与未来CNN预测的初始配置充分匹配，同时（2）最大化目标验证者网络的输出。最后，通过遵循由精确的相机配置序列产生的轨迹，我们获得完整的12D运动序列。
 我们的模型生成逼真的篮球运动序列，捕捉真实球员的目标，超越标准的深度学习方法，如递归神经网络（RNN），长期短期记忆网络（LSTM）和生成对抗网络（GAN）。

##### URL
[http://arxiv.org/abs/1803.01413](http://arxiv.org/abs/1803.01413)

##### PDF
[http://arxiv.org/pdf/1803.01413](http://arxiv.org/pdf/1803.01413)

