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


##### URL
[https://arxiv.org/abs/1604.03356](https://arxiv.org/abs/1604.03356)

##### PDF
[https://arxiv.org/pdf/1604.03356](https://arxiv.org/pdf/1604.03356)

