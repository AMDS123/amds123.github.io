---
layout: post
title: "Contextual Relationship-based Activity Segmentation on an Event Stream in the IoT Environment with Multi-user Activities"
date: 2016-09-20 05:37:56
categories: arXiv_CV
tags: arXiv_CV Segmentation RNN Relation Recognition
author: Minkyoung Cho, Younggi Kim, Younghee Lee
mathjax: true
---

* content
{:toc}

##### Abstract
The human activity recognition in the IoT environment plays the central role in the ambient assisted living, where the human activities can be represented as a concatenated event stream generated from various smart objects. From the concatenated event stream, each activity should be distinguished separately for the human activity recognition to provide services that users may need. In this regard, accurately segmenting the entire stream at the precise boundary of each activity is indispensable high priority task to realize the activity recognition. Multiple human activities in an IoT environment generate varying event stream patterns, and the unpredictability of these patterns makes them include redundant or missing events. In dealing with this complex segmentation problem, we figured out that the dynamic and confusing patterns cause major problems due to: inclusive event stream, redundant events, and shared events. To address these problems, we exploited the contextual relationships associated with the activity status about either ongoing or terminated/started. To discover the intrinsic relationships between the events in a stream, we utilized the LSTM model by rendering it for the activity segmentation. Then, the inferred boundaries were revised by our validation algorithm for a bit shifted boundaries. Our experiments show the surprising result of high accuracy above 95%, on our own testbed with various smart objects. This is superior to the prior works that even do not assume the environment with multi-user activities, where their accuracies are slightly above 80% in their test environment. It proves that our work is feasible enough to be applied in the IoT environment.

##### Abstract (translated by Google)
物联网环境中的人类活动识别在环境辅助生活中起着核心作用，在这种环境辅助生活中，人类活动可以表现为由各种智能物体产生的连接事件流。从连接的事件流中，每个活动应该分别区分人类活动识别以提供用户可能需要的服务。在这方面，准确地将整个流划分到每个活动的精确边界是实现活动识别不可或缺的高度优先任务。物联网环境中的多个人类活动会产生不同的事件流模式，而这些模式的不可预测性使得它们包含多余或丢失的事件。在处理这个复杂的分割问题时，我们发现动态和混乱的模式会引起重大问题，包括：包容事件流，冗余事件和共享事件。为了解决这些问题，我们利用与正在进行的或已终止/已开始的活动状态相关的上下文关系。为了发现流中事件之间的内在联系，我们利用LSTM模型进行活动分割。然后，通过我们的验证算法对推断的边界进行修改，以获得位移边界。我们的实验显示了在95％以上的高精度的惊人结果，在我们自己的具有各种智能对象的测试平台上。这比以前的作品还要优越，即使不考虑多用户活动的环境，其测试环境的准确度略高于80％。这证明了我们的工作足以应用于物联网环境。

##### URL
[https://arxiv.org/abs/1609.06024](https://arxiv.org/abs/1609.06024)

##### PDF
[https://arxiv.org/pdf/1609.06024](https://arxiv.org/pdf/1609.06024)

