---
layout: post
title: "Vertex Coloring with Communication and Local Memory Constraints in Synchronous Broadcast Networks"
date: 2016-04-12 11:56:07
categories: arXiv_CV
tags: arXiv_CV Attention
author: Hicham Lakhlef (ASAP), Michel Raynal (ASAP), François Taïani (ASAP)
mathjax: true
---

* content
{:toc}

##### Abstract
The vertex coloring problem has received a lot of attention in the context of synchronous round-based systems where, at each round, a process can send a message to all its neighbors, and receive a message from each of them. Hence, this communication model is particularly suited to point-to-point communication channels. Several vertex coloring algorithms suited to these systems have been proposed. They differ mainly in the number of rounds they require and the number of colors they use. This paper considers a broadcast/receive communication model in which message collisions and message conflicts can occur (a collision occurs when, during the same round, messages are sent to the same process by too many neighbors; a conflict occurs when a process and one of its neighbors broadcast during the same round). This communication model is suited to systems where processes share communication bandwidths. More precisely,the paper considers the case where, during a round, a process may either broadcast a message to its neighbors or receive a message from at most $m$ of them. This captures communication-related constraints or a local memory constraint stating that, whatever the number of neighbors of a process, its local memory allows it to receive and store at most $m$ messages during each round. The paper defines first the corresponding generic vertex multi-coloring problem (a vertex can have several colors). It focuses then on tree networks, for which it presents a lower bound on the number of colors $K$ that are necessary (namely, $K=\lceil\frac{\Delta}{m}\rceil+1$, where $\Delta$ is the maximal degree of the communication graph), and an ssociated coloring algorithm, which is optimal with respect to $K$.

##### Abstract (translated by Google)
顶点着色问题在同步的基于轮的系统的环境中受到了很多的关注，在每一轮中，一个进程可以向其所有的邻居发送消息，并且从每个邻居接收消息。因此，这种通信模式特别适用于点对点的通信信道。已经提出了适合于这些系统的几种顶点着色算法。它们的主要区别在于需要的回合数量和使用的颜色数量。本文考虑一种广播/接收通信模型，其中可能发生消息冲突和消息冲突（在同一回合中，消息被太多邻居发送到相同进程时发生冲突;当进程和其邻居在同一回合播出）。这种通信模式适用于进程共享通信带宽的系统。更确切地说，本文考虑的情况是，在一个回合中，一个进程可以向其邻居广播消息或接收最多$ m $的消息。这捕获了与通信相关的约束或本地内存约束，指出无论进程的邻居数是多少，其本地内存都允许它在每一轮中接收和存储至多$ m $个消息。本文首先定义了相应的通用顶点多色问题（一个顶点可以有多种颜色）。它着重于树型网络，为此它在必要的颜色数量$ K $（即$ K = \ lceil \ frac {\ Delta} {m} \ rceil + 1 $，其中$ \ Delta $是通信图的最大程度），以及相对于$ K $最优的相关着色算法。

##### URL
[https://arxiv.org/abs/1604.03356](https://arxiv.org/abs/1604.03356)

##### PDF
[https://arxiv.org/pdf/1604.03356](https://arxiv.org/pdf/1604.03356)

