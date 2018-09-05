---
layout: post
title: "Improving the Expressiveness of Deep Learning Frameworks with Recursion"
date: 2018-09-04 08:31:21
categories: arXiv_AI
tags: arXiv_AI Inference Deep_Learning Relation
author: Eunji Jeong, Joo Seong Jeong, Soojeong Kim, Gyeong-In Yu, Byung-Gon Chun
mathjax: true
---

* content
{:toc}

##### Abstract
Recursive neural networks have widely been used by researchers to handle applications with recursively or hierarchically structured data. However, embedded control flow deep learning frameworks such as TensorFlow, Theano, Caffe2, and MXNet fail to efficiently represent and execute such neural networks, due to lack of support for recursion. In this paper, we add recursion to the programming model of existing frameworks by complementing their design with recursive execution of dataflow graphs as well as additional APIs for recursive definitions. Unlike iterative implementations, which can only understand the topological index of each node in recursive data structures, our recursive implementation is able to exploit the recursive relationships between nodes for efficient execution based on parallel computation. We present an implementation on TensorFlow and evaluation results with various recursive neural network models, showing that our recursive implementation not only conveys the recursive nature of recursive neural networks better than other implementations, but also uses given resources more effectively to reduce training and inference time.

##### Abstract (translated by Google)
递归神经网络已被研究人员广泛用于处理具有递归或分层结构数据的应用程序。然而，由于缺乏对递归的支持，嵌入式控制流深度学习框架（如TensorFlow，Theano，Caffe2和MXNet）无法有效地表示和执行此类神经网络。在本文中，我们通过递归执行数据流图以及用于递归定义的附加API来补充其设计，从而将递归添加到现有框架的编程模型中。与迭代实现不同，迭代实现只能理解递归数据结构中每个节点的拓扑索引，我们的递归实现能够利用节点之间的递归关系，以便基于并行计算进行高效执行。我们使用各种递归神经网络模型呈现TensorFlow和评估结果的实现，表明我们的递归实现不仅比其他实现更好地传达递归神经网络的递归性质，而且还更有效地使用给定资源来减少训练和推理时间。

##### URL
[http://arxiv.org/abs/1809.00832](http://arxiv.org/abs/1809.00832)

##### PDF
[http://arxiv.org/pdf/1809.00832](http://arxiv.org/pdf/1809.00832)

