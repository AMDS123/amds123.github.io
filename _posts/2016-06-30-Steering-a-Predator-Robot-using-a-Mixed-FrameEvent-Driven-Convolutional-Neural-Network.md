---
layout: post
title: "Steering a Predator Robot using a Mixed Frame/Event-Driven Convolutional Neural Network"
date: 2016-06-30 11:17:00
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning
author: Diederik Paul Moeys, Federico Corradi, Emmett Kerr, Philip Vance, Gautham Das, Daniel Neil, Dermot Kerr, Tobi Delbruck
mathjax: true
---

* content
{:toc}

##### Abstract
This paper describes the application of a Convolutional Neural Network (CNN) in the context of a predator/prey scenario. The CNN is trained and run on data from a Dynamic and Active Pixel Sensor (DAVIS) mounted on a Summit XL robot (the predator), which follows another one (the prey). The CNN is driven by both conventional image frames and dynamic vision sensor "frames" that consist of a constant number of DAVIS ON and OFF events. The network is thus "data driven" at a sample rate proportional to the scene activity, so the effective sample rate varies from 15 Hz to 240 Hz depending on the robot speeds. The network generates four outputs: steer right, left, center and non-visible. After off-line training on labeled data, the network is imported on the on-board Summit XL robot which runs jAER and receives steering directions in real time. Successful results on closed-loop trials, with accuracies up to 87% or 92% (depending on evaluation criteria) are reported. Although the proposed approach discards the precise DAVIS event timing, it offers the significant advantage of compatibility with conventional deep learning technology without giving up the advantage of data-driven computing.

##### Abstract (translated by Google)
本文描述了卷积神经网络（CNN）在捕食者/猎物情景中的应用。美国有线电视新闻网（CNN）训练并运行安装在Summit XL机器人（捕食者）上的动态和有源像素传感器（DAVIS）的数据，该机器人跟随另一个（猎物）。 CNN由传统图像帧和动态视觉传感器“帧”驱动，帧由恒定数量的DAVIS ON和OFF事件组成。网络因此是以与场景活动成比例的采样率“数据驱动”的，所以根据机器人的速度，有效采样率从15Hz到240Hz变化。网络产生四个输出：左转，右转，中心和不可见。在标签数据的离线培训之后，网络通过机载的Summit XL机器人导入，运行jAER并实时接收转向。报告的闭环试验取得了成功的结果，精度高达87％或92％（取决于评估标准）。虽然所提出的方法丢弃了精确的DAVIS事件时序，但它提供了与传统的深度学习技术兼容的显着优势，而不会放弃数据驱动计算的优势。

##### URL
[https://arxiv.org/abs/1606.09433](https://arxiv.org/abs/1606.09433)

##### PDF
[https://arxiv.org/pdf/1606.09433](https://arxiv.org/pdf/1606.09433)

