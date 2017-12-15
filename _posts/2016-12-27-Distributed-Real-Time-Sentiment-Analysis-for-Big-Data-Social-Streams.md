---
layout: post
title: "Distributed Real-Time Sentiment Analysis for Big Data Social Streams"
date: 2016-12-27 09:10:18
categories: arXiv_CL
tags: arXiv_CL Sentiment Classification
author: Amir Hossein Akhavan Rahnama
mathjax: true
---

* content
{:toc}

##### Abstract
Big data trend has enforced the data-centric systems to have continuous fast data streams. In recent years, real-time analytics on stream data has formed into a new research field, which aims to answer queries about what-is-happening-now with a negligible delay. The real challenge with real-time stream data processing is that it is impossible to store instances of data, and therefore online analytical algorithms are utilized. To perform real-time analytics, pre-processing of data should be performed in a way that only a short summary of stream is stored in main memory. In addition, due to high speed of arrival, average processing time for each instance of data should be in such a way that incoming instances are not lost without being captured. Lastly, the learner needs to provide high analytical accuracy measures. Sentinel is a distributed system written in Java that aims to solve this challenge by enforcing both the processing and learning process to be done in distributed form. Sentinel is built on top of Apache Storm, a distributed computing platform. Sentinels learner, Vertical Hoeffding Tree, is a parallel decision tree-learning algorithm based on the VFDT, with ability of enabling parallel classification in distributed environments. Sentinel also uses SpaceSaving to keep a summary of the data stream and stores its summary in a synopsis data structure. Application of Sentinel on Twitter Public Stream API is shown and the results are discussed.

##### Abstract (translated by Google)
大数据趋势已经强化了以数据为中心的系统来持续快速的数据流。近年来，流数据的实时分析已经形成了一个新的研究领域，其目的是回答关于发生什么事情的疑问，现在可以忽略不计的延迟。实时流数据处理的真正挑战是不可能存储数据实例，因此使用在线分析算法。为了执行实时分析，数据的预处理应该以只将流的简短摘要存储在主存储器中的方式来执行。另外，由于到达的高速度，每个数据实例的平均处理时间应该是这样的，即传入实例不被丢失而不被捕获。最后，学习者需要提供高分析准确度的措施。 Sentinel是一个用Java编写的分布式系统，旨在通过强制执行分布式处理和学习过程来解决这一挑战。 Sentinel建立在分布式计算平台Apache Storm之上。哨兵学习者Vertical Hoeffding Tree是一种基于VFDT的并行决策树学习算法，具有在分布式环境中实现并行分类的能力。 Sentinel还使用SpaceSaving来保存数据流的摘要并将其摘要存储在摘要数据结构中。显示了Sentinel在Twitter公共流API上的应用，并讨论了结果。

##### URL
[https://arxiv.org/abs/1612.08543](https://arxiv.org/abs/1612.08543)

##### PDF
[https://arxiv.org/pdf/1612.08543](https://arxiv.org/pdf/1612.08543)

