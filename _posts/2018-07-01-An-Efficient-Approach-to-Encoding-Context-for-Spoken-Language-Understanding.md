---
layout: post
title: "An Efficient Approach to Encoding Context for Spoken Language Understanding"
date: 2018-07-01 04:11:18
categories: arXiv_CL
tags: arXiv_CL RNN Memory_Networks
author: Raghav Gupta, Abhinav Rastogi, Dilek Hakkani-Tur
mathjax: true
---

* content
{:toc}

##### Abstract
In task-oriented dialogue systems, spoken language understanding, or SLU, refers to the task of parsing natural language user utterances into semantic frames. Making use of context from prior dialogue history holds the key to more effective SLU. State of the art approaches to SLU use memory networks to encode context by processing multiple utterances from the dialogue at each turn, resulting in significant trade-offs between accuracy and computational efficiency. On the other hand, downstream components like the dialogue state tracker (DST) already keep track of the dialogue state, which can serve as a summary of the dialogue history. In this work, we propose an efficient approach to encoding context from prior utterances for SLU. More specifically, our architecture includes a separate recurrent neural network (RNN) based encoding module that accumulates dialogue context to guide the frame parsing sub-tasks and can be shared between SLU and DST. In our experiments, we demonstrate the effectiveness of our approach on dialogues from two domains.

##### Abstract (translated by Google)
在面向任务的对话系统中，口语理解或SLU指的是将自然语言用户话语解析为语义帧的任务。利用先前对话历史中的背景是更有效的SLU的关键。 SLU的现有技术方法使用存储器网络通过在每个转弯处处理来自对话的多个话语来编码上下文，导致准确性和计算效率之间的显着折衷。另一方面，诸如对话状态跟踪器（DST）的下游组件已经跟踪对话状态，其可以用作对话历史的摘要。在这项工作中，我们提出了一种从SLU的先前话语中编码上下文的有效方法。更具体地，我们的体系结构包括基于单独的基于递归神经网络（RNN）的编码模块，其累积对话上下文以指导帧解析子任务并且可以在SLU和DST之间共享。在我们的实验中，我们证明了我们的方法在两个领域的对话中的有效性。

##### URL
[http://arxiv.org/abs/1807.00267](http://arxiv.org/abs/1807.00267)

##### PDF
[http://arxiv.org/pdf/1807.00267](http://arxiv.org/pdf/1807.00267)

