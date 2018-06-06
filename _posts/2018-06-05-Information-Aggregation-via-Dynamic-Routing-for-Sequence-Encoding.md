---
layout: post
title: "Information Aggregation via Dynamic Routing for Sequence Encoding"
date: 2018-06-05 05:34:15
categories: arXiv_CL
tags: arXiv_CL Attention Text_Classification RNN Classification
author: Jingjing Gong, Xipeng Qiu, Shaojing Wang, Xuanjing Huang
mathjax: true
---

* content
{:toc}

##### Abstract
While much progress has been made in how to encode a text sequence into a sequence of vectors, less attention has been paid to how to aggregate these preceding vectors (outputs of RNN/CNN) into fixed-size encoding vector. Usually, a simple max or average pooling is used, which is a bottom-up and passive way of aggregation and lack of guidance by task information. In this paper, we propose an aggregation mechanism to obtain a fixed-size encoding with a dynamic routing policy. The dynamic routing policy is dynamically deciding that what and how much information need be transferred from each word to the final encoding of the text sequence. Following the work of Capsule Network, we design two dynamic routing policies to aggregate the outputs of RNN/CNN encoding layer into a final encoding vector. Compared to the other aggregation methods, dynamic routing can refine the messages according to the state of final encoding vector. Experimental results on five text classification tasks show that our method outperforms other aggregating models by a significant margin. Related source code is released on our github page.

##### Abstract (translated by Google)
虽然在如何将文本序列编码成矢量序列方面取得了很大进展，但是如何将这些前面的矢量（RNN / CNN的输出）聚合成固定尺寸的编码矢量却没有引起足够的重视。通常使用简单的最大或平均汇总，这是一种自下而上和被动的聚合方式，缺乏任务信息的指导。在本文中，我们提出了一种使用动态路由策略获得固定大小编码的聚合机制。动态路由策略动态地决定需要从每个单词向文本序列的最终编码传输多少信息和多少信息。在Capsule Network的工作之后，我们设计了两个动态路由策略，将RNN / CNN编码层的输出聚合成最终的编码向量。与其他聚合方法相比，动态路由可以根据最终编码矢量的状态来优化消息。对五个文本分类任务的实验结果表明，我们的方法在性能上优于其他聚合模型。相关的源代码在我们的github页面上发布。

##### URL
[http://arxiv.org/abs/1806.01501](http://arxiv.org/abs/1806.01501)

##### PDF
[http://arxiv.org/pdf/1806.01501](http://arxiv.org/pdf/1806.01501)

