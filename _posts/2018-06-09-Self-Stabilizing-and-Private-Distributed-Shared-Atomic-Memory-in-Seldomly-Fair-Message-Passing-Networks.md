---
layout: post
title: "Self-Stabilizing and Private Distributed Shared Atomic Memory in Seldomly Fair Message Passing Networks"
date: 2018-06-09 16:08:54
categories: arXiv_CV
tags: arXiv_CV Knowledge
author: Shlomi Dolev, Thomas Petig, Elad Michael Schiller
mathjax: true
---

* content
{:toc}

##### Abstract
We study the problem of privately emulating shared memory in message-passing networks. The system includes clients that store and retrieve replicated information on N servers, out of which e are malicious. When a client access a malicious server, the data field of that server response might be different than the value it originally stored. However, all other control variables in the server reply and protocol actions are according to the server algorithm. For the coded atomic storage (CAS) algorithms by Cadambe et al., we present an enhancement that ensures no information leakage and malicious fault-tolerance. We also consider recovery after the occurrence of transient faults that violate the assumptions according to which the system is to behave. After their last occurrence, transient faults leave the system in an arbitrary state (while the program code stays intact). We present a self-stabilizing algorithm, which recovers after the occurrence of transient faults. This addition to Cadambe et al. considers asynchronous settings as long as no transient faults occur. The recovery from transient faults that bring the system counters (close) to their maximal values may include the use of a global reset procedure, which requires the system run to be controlled by a fair scheduler. After the recovery period, the safety properties are provided for asynchronous system runs that are not necessarily controlled by fair schedulers. Since the recovery period is bounded and the occurrence of transient faults is extremely rare, we call this design criteria self-stabilization in the presence of seldom fairness. Our self-stabilizing algorithm uses a bounded storage during asynchronous executions (that are not necessarily fair). To the best of our knowledge, we are the first to address privacy and self-stabilization in the context of emulating atomic shared memory in networked systems.

##### Abstract (translated by Google)
我们研究在消息传递网络中私下模拟共享内存的问题。该系统包括在N台服务器上存储和检索复制信息的客户端，其中e是恶意的。当客户端访问恶意服务器时，该服务器响应的数据字段可能与其最初存储的值不同。但是，服务器回复和协议操作中的所有其他控制变量都是根据服务器算法。对于Cadambe等人的编码原子存储（CAS）算法，我们提出了一种增强，确保没有信息泄漏和恶意容错。我们还考虑在发生瞬时故障后恢复，这些故障违反了系统应该遵循的假设。在最后一次发生后，瞬态故障将使系统处于任意状态（程序代码保持不变）。我们提出了一种自稳定算法，在瞬态故障发生后恢复。 Cadambe等人补充了这一点。只要没有发生瞬态故障，就会考虑异步设置。从使系统计数器（关闭）达到其最大值的瞬时故障中恢复可能包括使用全局重置过程，这需要系统运行由公平调度程序控制。恢复期之后，安全属性提供给异步系统运行，不一定由公平调度程序控制。由于恢复期是有限的，并且暂时性故障的发生极其罕见，我们称这种设计标准在很少公平的情况下自稳定。我们的自稳定算法在异步执行期间使用有界存储（不一定公平）。就我们所知，我们是第一个在模拟网络系统中的原子共享内存的环境中解决隐私和自稳的方法。

##### URL
[https://arxiv.org/abs/1806.03498](https://arxiv.org/abs/1806.03498)

##### PDF
[https://arxiv.org/pdf/1806.03498](https://arxiv.org/pdf/1806.03498)

