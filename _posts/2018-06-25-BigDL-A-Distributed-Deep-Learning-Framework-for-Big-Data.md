---
layout: post
title: "BigDL: A Distributed Deep Learning Framework for Big Data"
date: 2018-06-25 02:57:37
categories: arXiv_AI
tags: arXiv_AI Object_Detection Deep_Learning Detection Recommendation
author: Jason Dai, Yiheng Wang, Xin Qiu, Ding Ding, Yao Zhang, Yanzhang Wang, Xianyan Jia, Cherry Zhang, Yan Wan, Zhichao Li, Jiao Wang, Shengsheng Huang, Zhongyuan Wu, Yang Wang, Yuhao Yang, Bowen She, Dongjie Shi, Qi Lu, Kai Huang, Guoqiong Song
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present BigDL, a distributed deep learning framework for Big Data platforms and workflows. It is implemented on top of Apache Spark, and allows users to write their deep learning applications as standard Spark programs (running directly on large-scale big data clusters in a distributed fashion). It provides an expressive, "data-analytics integrated" deep learning programming model, so that users can easily build the end-to-end analytics + AI pipelines under a unified programming paradigm; by implementing an AllReduce like operation using existing primitives in Spark (e.g., shuffle, broadcast, and in-memory data persistence), it also provides a highly efficient "parameter server" style architecture, so as to achieve highly scalable, data-parallel distributed training. Since its initial open source release, BigDL users have built many analytics and deep learning applications (e.g., object detection, sequence-to-sequence generation, visual similarity, neural recommendations, fraud detection, etc.) on Spark.

##### Abstract (translated by Google)
在本文中，我们介绍BigDL，这是一个面向大数据平台和工作流的分布式深度学习框架。它在Apache Spark之上实现，并允许用户将其深度学习应用程序编写为标准Spark程序（以分布式方式直接在大型大数据集群上运行）。它提供了富有表现力的“数据分析集成”深度学习编程模型，以便用户可以在统一的编程范例下轻松构建端到端分析+ AI管道;通过使用Spark中现有的原语（例如，混洗，广播和内存中的数据持久化）实现类似AllReduce的操作，它还提供了一种高效的“参数服务器”式体系结构，以实现高度可伸缩的数据并行分布式训练。自从最初的开源版本以来，BigDL用户已经在Spark上构建了许多分析和深度学习应用程序（例如对象检测，序列到序列生成，视觉相似性，神经推荐，欺诈检测等）。

##### URL
[http://arxiv.org/abs/1804.05839](http://arxiv.org/abs/1804.05839)

##### PDF
[http://arxiv.org/pdf/1804.05839](http://arxiv.org/pdf/1804.05839)

