---
layout: post
title: "Heart Beat Characterization from Ballistocardiogram Signals using Extended Functions of Multiple Instances"
date: 2016-05-16 02:30:28
categories: arXiv_CV
tags: arXiv_CV GAN Detection
author: Changzhe Jiao, Princess Lyons, Alina Zare, Licet Rosales, Marjorie Skubic
mathjax: true
---

* content
{:toc}

##### Abstract
A multiple instance learning (MIL) method, extended Function of Multiple Instances ($e$FUMI), is applied to ballistocardiogram (BCG) signals produced by a hydraulic bed sensor. The goal of this approach is to learn a personalized heartbeat "concept" for an individual. This heartbeat concept is a prototype (or "signature") that characterizes the heartbeat pattern for an individual in ballistocardiogram data. The $e$FUMI method models the problem of learning a heartbeat concept from a BCG signal as a MIL problem. This approach elegantly addresses the uncertainty inherent in a BCG signal e. g., misalignment between training data and ground truth, mis-collection of heartbeat by some transducers, etc. Given a BCG training signal coupled with a ground truth signal (e.g., a pulse finger sensor), training "bags" labeled with only binary labels denoting if a training bag contains a heartbeat signal or not can be generated. Then, using these bags, $e$FUMI learns a personalized concept of heartbeat for a subject as well as several non-heartbeat background concepts. After learning the heartbeat concept, heartbeat detection and heart rate estimation can be applied to test data. Experimental results show that the estimated heartbeat concept found by $e$FUMI is more representative and a more discriminative prototype of the heartbeat signals than those found by comparison MIL methods in the literature.

##### Abstract (translated by Google)
多实例学习（MIL）方法，扩展多重实例功能（$ e $ FUMI）适用于由液压床传感器产生的心冲击图（BCG）信号。这种方法的目标是为个人学习个性化的心跳“概念”。这个心跳概念是一个原型（或“签名”），描绘心冲击图数据中个体的心跳模式。 $ e $ FUMI方法将从BCG信号学习心跳概念的问题模拟为MIL问题。这种方法优雅地解决了BCG信号e中固有的不确定性。例如，训练数据和地面事实之间的偏差，某些换能器的心跳收集错误等。给定与地面真值信号（例如，脉搏手指传感器）耦合的BCG训练信号，训练仅标记有二进制可以生成表示训练包是否包含心跳信号的标签。然后，使用这些包，$ e $ FUMI学习一个主题的心跳的个性化概念以及几个非心跳的背景概念。学习心跳概念后，心跳检测和心率估计可以应用于测试数据。实验结果表明，$ e $ FUMI发现的估计心跳概念比文献中比较MIL方法所发现的心跳概念更具代表性，也是心脏信号判别性更强的原型。

##### URL
[https://arxiv.org/abs/1605.04634](https://arxiv.org/abs/1605.04634)

##### PDF
[https://arxiv.org/pdf/1605.04634](https://arxiv.org/pdf/1605.04634)

