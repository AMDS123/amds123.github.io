---
layout: post
title: "Deep fusion of visual signatures for client-server facial analysis"
date: 2016-11-09 10:48:58
categories: arXiv_CV
tags: arXiv_CV Face
author: Binod Bhattarai, Gaurav Sharma, Frederic Jurie
mathjax: true
---

* content
{:toc}

##### Abstract
Facial analysis is a key technology for enabling human-machine interaction. In this context, we present a client-server framework, where a client transmits the signature of a face to be analyzed to the server, and, in return, the server sends back various information describing the face e.g. is the person male or female, is she/he bald, does he have a mustache, etc. We assume that a client can compute one (or a combination) of visual features; from very simple and efficient features, like Local Binary Patterns, to more complex and computationally heavy, like Fisher Vectors and CNN based, depending on the computing resources available. The challenge addressed in this paper is to design a common universal representation such that a single merged signature is transmitted to the server, whatever be the type and number of features computed by the client, ensuring nonetheless an optimal performance. Our solution is based on learning of a common optimal subspace for aligning the different face features and merging them into a universal signature. We have validated the proposed method on the challenging CelebA dataset, on which our method outperforms existing state-of-the-art methods when rich representation is available at test time, while giving competitive performance when only simple signatures (like LBP) are available at test time due to resource constraints on the client.

##### Abstract (translated by Google)
面部分析是实现人机交互的关键技术。在这种情况下，我们提出一个客户端 - 服务器框架，其中客户端将要分析的脸部的签名发送到服务器，并且作为回应，服务器发回描述脸部的各种信息，例如，是男性还是女性，是否秃顶，是否有小胡子等。我们假设客户可以计算一个（或多个）视觉特征的组合。从非常简单高效的功能（如本地二进制模式）到更复杂和计算量更大的功能，如Fisher矢量和CNN（取决于可用的计算资源）。本文所讨论的挑战是设计一个通用的通用表示形式，使得一个合并的签名被传送到服务器，无论客户端计算的特征的类型和数量如何，确保了最佳的性能。我们的解决方案是基于学习一个共同的最佳子空间来对齐不同的脸部特征并将它们合并成一个通用签名。我们在具有挑战性的CelebA数据集上验证了所提出的方法，在测试时丰富的表示可用的情况下，我们的方法胜过了现有的最先进的方法，而在只有简单的签名（如LBP）测试时间由于客户端的资源限制。

##### URL
[https://arxiv.org/abs/1611.00142](https://arxiv.org/abs/1611.00142)

##### PDF
[https://arxiv.org/pdf/1611.00142](https://arxiv.org/pdf/1611.00142)

