---
layout: post
title: "Memory-efficient and Ultra-fast Network Lookup and Forwarding using Othello Hashing"
date: 2017-11-22 17:49:55
categories: arXiv_CV
tags: arXiv_CV
author: Ye Yu, Djamal Belazzougui, Chen Qian, Qin Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Network algorithms always prefer low memory cost and fast packet processing speed. Forwarding information base (FIB), as a typical network processing component, requires a scalable and memory-efficient algorithm to support fast lookups. In this paper, we present a new network algorithm, Othello Hashing, and its application of a FIB design called Concise, which uses very little memory to support ultra-fast lookups of network names. Othello Hashing and Concise make use of minimal perfect hashing and relies on the programmable network framework to support dynamic updates. Our conceptual contribution of Concise is to optimize the memory efficiency and query speed in the data plane and move the relatively complex construction and update components to the resource-rich control plane. We implemented Concise on three platforms. Experimental results show that Concise uses significantly smaller memory to achieve much faster query speed compared to existing solutions of network name lookups.

##### Abstract (translated by Google)
网络算法总是倾向于低内存成本和快速的数据包处理速度。转发信息库（FIB）作为一个典型的网络处理组件，需要一种可扩展且高效的内存算法来支持快速查找。在本文中，我们提出了一种新的网络算法Othello Hashing及其应用了一种名为Concise的FIB设计，​​它使用很少的内存来支持网络名称的超快速查找。奥瑟罗哈希和简洁利用最小的完美哈希，并依靠可编程网络框架来支持动态更新。 Concise的概念贡献是优化数据平面的内存效率和查询速度，将相对复杂的构建和更新组件移植到资源丰富的控制平面。我们在三个平台上实施了Concise。实验结果表明，与现有的网络名称查找解决方案相比，Concise使用更小的内存来实现更快的查询速度。

##### URL
[https://arxiv.org/abs/1608.05699](https://arxiv.org/abs/1608.05699)

##### PDF
[https://arxiv.org/pdf/1608.05699](https://arxiv.org/pdf/1608.05699)

