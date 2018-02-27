---
layout: post
title: "Kitsune: An Ensemble of Autoencoders for Online Network Intrusion Detection"
date: 2018-02-25 21:42:56
categories: arXiv_AI
tags: arXiv_AI Object_Detection Detection
author: Yisroel Mirsky, Tomer Doitshman, Yuval Elovici, Asaf Shabtai
mathjax: true
---

* content
{:toc}

##### Abstract
Neural networks have become an increasingly popular solution for network intrusion detection systems (NIDS). Their capability of learning complex patterns and behaviors make them a suitable solution for differentiating between normal traffic and network attacks. However, a drawback of neural networks is the amount of resources needed to train them. Many network gateways and routers devices, which could potentially host an NIDS, simply do not have the memory or processing power to train and sometimes even execute such models. More importantly, the existing neural network solutions are trained in a supervised manner. Meaning that an expert must label the network traffic and update the model manually from time to time. 
 In this paper, we present Kitsune: a plug and play NIDS which can learn to detect attacks on the local network, without supervision, and in an efficient online manner. Kitsune's core algorithm (KitNET) uses an ensemble of neural networks called autoencoders to collectively differentiate between normal and abnormal traffic patterns. KitNET is supported by a feature extraction framework which efficiently tracks the patterns of every network channel. Our evaluations show that Kitsune can detect various attacks with a performance comparable to offline anomaly detectors, even on a Raspberry PI. This demonstrates that Kitsune can be a practical and economic NIDS.

##### Abstract (translated by Google)
神经网络已经成为网络入侵检测系统（NIDS）日益流行的解决方案。他们学习复杂模式和行为的能力使其成为区分正常流量和网络攻击的合适解决方案。然而，神经网络的一个缺点是训练它们所需的资源量。许多可能托管NIDS的网关和路由器设备根本没有内存或处理能力来训练甚至执行这些模型。更重要的是，现有的神经网络解决方案是以监督的方式进行训练的。这意味着专家必须不时手动标记网络流量并更新模型。
 在本文中，我们介绍Kitsune：一种即插即用的NIDS，它可以学习检测本地网络上的攻击，而无需监督，并以高效的在线方式。 Kitsune的核心算法（KitNET）使用称为自动编码器的神经网络集合来统一区分正常和异常流量模式。 KitNET由特征提取框架支持，该框架有效地跟踪每个网络通道的模式。我们的评估表明，Kitsune可以检测各种攻击，其性能可与离线异常检测器相媲美，即使在Raspberry PI上也是如此。这表明Kitsune可以成为实用和经济的NIDS。

##### URL
[http://arxiv.org/abs/1802.09089](http://arxiv.org/abs/1802.09089)

##### PDF
[http://arxiv.org/pdf/1802.09089](http://arxiv.org/pdf/1802.09089)

