---
layout: post
title: "NetSpectre: Read Arbitrary Memory over Network"
date: 2018-07-27 11:13:18
categories: arXiv_CV
tags: arXiv_CV
author: Michael Schwarz, Martin Schwarzl, Moritz Lipp, Daniel Gruss
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present NetSpectre, a generic remote Spectre variant 1 attack. For this purpose, we demonstrate the first access-driven remote Evict+Reload cache attack over network, leaking 15 bits per hour. Beyond retrofitting existing attacks to a network scenario, we also demonstrate the first Spectre attack which does not use a cache covert channel. Instead, we present a novel high-performance AVX-based covert channel that we use in our cache-free Spectre attack. We show that in particular remote Spectre attacks perform significantly better with the AVX-based covert channel, leaking 60 bits per hour from the target system. We verified that our NetSpectre attacks work in local-area networks as well as between virtual machines in the Google cloud. NetSpectre marks a paradigm shift from local attacks, to remote attacks, exposing a much wider range and larger number of devices to Spectre attacks. Spectre attacks now must also be considered on devices which do not run any potentially attacker-controlled code at all. We show that especially in this remote scenario, attacks based on weaker gadgets which do not leak actual data, are still very powerful to break address-space layout randomization remotely. Several of the Spectre gadgets we discuss are more versatile than anticipated. In particular, value-thresholding is a technique we devise, which leaks a secret value without the typical bit selection mechanisms. We outline challenges for future research on Spectre attacks and Spectre mitigations.

##### Abstract (translated by Google)
在本文中，我们介绍了NetSpectre，一种通用的远程幽灵变种1攻击。为此，我们演示了第一个通过网络访问驱动的远程Evict + Reload缓存攻击，每小时泄漏15位。除了将现有攻击改造为网络场景之外，我们还演示了第一个不使用缓存隐藏通道的Spectre攻击。相反，我们提出了一种新的基于AVX的高性能隐蔽通道，我们在无缓存的Spectre攻击中使用它。我们表明，特别是远程Spectre攻击在基于AVX的隐蔽通道上表现得更好，每小时从目标系统泄漏60位。我们验证了我们的NetSpectre攻击在局域网中以及在Google云中的虚拟机之间工作。 NetSpectre标志着从本地攻击到远程攻击的范式转变，将更广泛的范围和更多数量的设备暴露给Spectre攻击。现在还必须在不运行任何潜在攻击者控制代码的设备上考虑幽灵攻击。我们表明，特别是在这种远程场景中，基于较弱的小工具而不会泄漏实际数据的攻击仍然非常强大，可以远程打破地址空间布局随机化。我们讨论的几个Spectre小工具比预期的更通用。特别是，值阈值化是我们设计的一种技术，它在没有典型的位选择机制的情况下泄漏秘密值。我们概述了未来关于幽灵攻击和幽灵缓解的研究的挑战。

##### URL
[https://arxiv.org/abs/1807.10535](https://arxiv.org/abs/1807.10535)

##### PDF
[https://arxiv.org/pdf/1807.10535](https://arxiv.org/pdf/1807.10535)

