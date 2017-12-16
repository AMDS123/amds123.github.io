---
layout: post
title: "Joint Detection and Recounting of Abnormal Events by Learning Deep Generic Knowledge"
date: 2017-09-26 16:38:03
categories: arXiv_CV
tags: arXiv_CV Object_Detection Knowledge CNN Detection
author: Ryota Hinami, Tao Mei, Shin'ichi Satoh
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the problem of joint detection and recounting of abnormal events in videos. Recounting of abnormal events, i.e., explaining why they are judged to be abnormal, is an unexplored but critical task in video surveillance, because it helps human observers quickly judge if they are false alarms or not. To describe the events in the human-understandable form for event recounting, learning generic knowledge about visual concepts (e.g., object and action) is crucial. Although convolutional neural networks (CNNs) have achieved promising results in learning such concepts, it remains an open question as to how to effectively use CNNs for abnormal event detection, mainly due to the environment-dependent nature of the anomaly detection. In this paper, we tackle this problem by integrating a generic CNN model and environment-dependent anomaly detectors. Our approach first learns CNN with multiple visual tasks to exploit semantic information that is useful for detecting and recounting abnormal events. By appropriately plugging the model into anomaly detectors, we can detect and recount abnormal events while taking advantage of the discriminative power of CNNs. Our approach outperforms the state-of-the-art on Avenue and UCSD Ped2 benchmarks for abnormal event detection and also produces promising results of abnormal event recounting.

##### Abstract (translated by Google)
本文针对视频中异常事件的联合检测和重新记录问题。记录异常事件，即解释为什么被判断为异常，是视频监控中一个未被发现但是关键的任务，因为它有助于人类观察者快速判断是否是误报。为了描述以人类可理解的形式进行事件叙述的事件，学习关于视觉概念（例如，对象和行为）的通用知识是至关重要的。尽管卷积神经网络（CNNs）在学习这些概念方面取得了令人鼓舞的成果，但是如何有效地将CNN用于异常事件检测仍然是一个悬而未决的问题，主要是由于异常检测的环境依赖性。在本文中，我们通过整合一个通用的CNN模型和环境依赖的异常探测器来解决这个问题。我们的方法首先学习CNN与多个视觉任务利用语义信息，是有用的检测和重新计数异常事件。通过将模型适当地插入异常检测器，我们可以利用CNN的判别能力来检测和重新记录异常事件。我们的方法胜过了用于异常事件检测的Avenue和UCSD Ped2基准的最新技术，并且还产生了有希望的异常事件重新记录结果。

##### URL
[https://arxiv.org/abs/1709.09121](https://arxiv.org/abs/1709.09121)

##### PDF
[https://arxiv.org/pdf/1709.09121](https://arxiv.org/pdf/1709.09121)

