---
layout: post
title: "Click-Through Rate Prediction with the User Memory Network"
date: 2019-07-09 03:40:07
categories: arXiv_CV
tags: arXiv_CV RNN Prediction
author: Wentao Ouyang, Xiuwu Zhang, Shukui Ren, Li Li, Zhaojie Liu, Yanlong Du
mathjax: true
---

* content
{:toc}

##### Abstract
Click-through rate (CTR) prediction is a critical task in online advertising systems. Models like Deep Neural Networks (DNNs) are simple but stateless. They consider each target ad independently and cannot directly extract useful information contained in users' historical ad impressions and clicks. In contrast, models like Recurrent Neural Networks (RNNs) are stateful but complex. They model temporal dependency between users' sequential behaviors and can achieve improved prediction performance than DNNs. However, both the offline training and online prediction process of RNNs are much more complex and time-consuming. In this paper, we propose Memory Augmented DNN (MA-DNN) for practical CTR prediction services. In particular, we create two external memory vectors for each user, memorizing high-level abstractions of what a user possibly likes and dislikes. The proposed MA-DNN achieves a good compromise between DNN and RNN. It is as simple as DNN, but has certain ability to exploit useful information contained in users' historical behaviors as RNN. Both offline and online experiments demonstrate the effectiveness of MA-DNN for practical CTR prediction services. Actually, the memory component can be augmented to other models as well (e.g., the Wide&Deep model).

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1907.04667](https://arxiv.org/abs/1907.04667)

##### PDF
[https://arxiv.org/pdf/1907.04667](https://arxiv.org/pdf/1907.04667)

