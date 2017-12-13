---
layout: post
title: "Memory-Assisted Universal Compression of Network Flows"
date: 2012-03-30 17:16:41
categories: arXiv_CV
tags: arXiv_CV Knowledge
author: Mohsen Sardari, Ahmad Beirami, Faramarz Fekri
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, the existence of considerable amount of redundancy in the Internet traffic has stimulated the deployment of several redundancy elimination techniques within the network. These techniques are often based on either packet-level Redundancy Elimination (RE) or Content-Centric Networking (CCN). However, these techniques cannot exploit sub-packet redundancies. Further, other alternative techniques such as the end-to-end universal compression solutions would not perform well either over the Internet traffic, as such techniques require infinite length traffic to effectively remove redundancy. This paper proposes a memory-assisted universal compression technique that holds a significant promise for reducing the amount of traffic in the networks. The proposed work is based on the observation that if a source is to be compressed and sent over a network, the associated universal code entails a substantial overhead in transmission due to finite length traffic. However, intermediate nodes can learn the source statistics and this can be used to reduce the cost of describing the source statistics, reducing the transmission overhead for such traffics. We present two algorithms (statistical and dictionary-based) for the memory-assisted universal lossless compression of information sources. These schemes are universal in the sense that they do not require any prior knowledge of the traffic's statistical distribution. We demonstrate the effectiveness of both algorithms and characterize the memorization gain using the real Internet traces. Furthermore, we apply these compression schemes to Internet-like power-law graphs and solve the routing problem for compressed flows.

##### Abstract (translated by Google)
最近，因特网流量中存在相当多的冗余，激发了在网络内部署多种冗余消除技术。这些技术通常基于分组级冗余消除（RE）或以内容为中心的网络（CCN）。但是，这些技术不能利用子包冗余。此外，诸如端到端通用压缩解决方案之类的其他替代技术在互联网业务上将不能很好地执行，因为这样的技术需要无限长的业务来有效地移除冗余。本文提出了一种内存辅助通用压缩技术，对于减少网络中的通信量具有重要的承诺。所提出的工作是基于这样的观察：如果一个信源将被压缩并通过一个网络发送，则相关的通用码会由于有限的长度业务量而在传输中带来大量的开销。但是，中间节点可以学习源统计信息，这可以用来降低描述源统计信息的成本，减少这种业务的传输开销。我们提出了两种算法（统计和字典为基础）的记忆辅助信息源的无损压缩。这些方案是普遍的，因为它们不需要事先知道交通的统计分布。我们证明了这两种算法的有效性，并使用真实的互联网痕迹来表征记忆增益。此外，我们将这些压缩方案应用于类似因特网的幂律图，并解决压缩流的路由问题。

##### URL
[https://arxiv.org/abs/1203.6864](https://arxiv.org/abs/1203.6864)

##### PDF
[https://arxiv.org/pdf/1203.6864](https://arxiv.org/pdf/1203.6864)

