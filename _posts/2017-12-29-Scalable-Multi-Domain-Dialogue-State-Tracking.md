---
layout: post
title: "Scalable Multi-Domain Dialogue State Tracking"
date: 2017-12-29 13:34:46
categories: arXiv_CL
tags: arXiv_CL Knowledge Ontology Tracking Transfer_Learning Deep_Learning
author: Abhinav Rastogi, Dilek Hakkani-Tur, Larry Heck
mathjax: true
---

* content
{:toc}

##### Abstract
Dialogue state tracking (DST) is a key component of task-oriented dialogue systems. DST estimates the user's goal at each user turn given the interaction until then. State of the art approaches for state tracking rely on deep learning methods, and represent dialogue state as a distribution over all possible slot values for each slot present in the ontology. Such a representation is not scalable when the set of possible values are unbounded (e.g., date, time or location) or dynamic (e.g., movies or usernames). Furthermore, training of such models requires labeled data, where each user turn is annotated with the dialogue state, which makes building models for new domains challenging. In this paper, we present a scalable multi-domain deep learning based approach for DST. We introduce a novel framework for state tracking which is independent of the slot value set, and represent the dialogue state as a distribution over a set of values of interest (candidate set) derived from the dialogue history or knowledge. Restricting these candidate sets to be bounded in size addresses the problem of slot-scalability. Furthermore, by leveraging the slot-independent architecture and transfer learning, we show that our proposed approach facilitates quick adaptation to new domains.

##### Abstract (translated by Google)
对话状态跟踪（DST）是面向任务的对话系统的关键组成部分。 DST估计每个用户在给定交互之前的用户目标。用于状态跟踪的现有技术方法依赖于深度学习方法，并且将对话状态表示为对本体中存在的每个时隙的所有可能的时隙值的分布。当可能值的集合是无界的（例如，日期，时间或位置）或动态的（例如，电影或用户名）时，这样的表示是不可缩放的。此外，对这些模型的训练需要标记数据，其中每个用户轮流用对话状态进行注释，这使得新领域的建模模型具有挑战性。在本文中，我们提出了一个可扩展的多领域深度学习的DST方法。我们引入了一种新颖的与时隙值集无关的状态跟踪框架，并将对话状态表示为对话历史或知识导出的一组感兴趣值（候选集）的分布。限制这些候选集合的大小限制了时隙可伸缩性的问题。此外，通过利用时隙无关架构和传输学习，我们表明，我们提出的方法有助于快速适应新的领域。

##### URL
[https://arxiv.org/abs/1712.10224](https://arxiv.org/abs/1712.10224)

##### PDF
[https://arxiv.org/pdf/1712.10224](https://arxiv.org/pdf/1712.10224)

