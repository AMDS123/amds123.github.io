---
layout: post
title: "DDRprog: A CLEVR Differentiable Dynamic Reasoning Programmer"
date: 2018-03-30 06:49:30
categories: arXiv_CV
tags: arXiv_CV RNN VQA
author: Joseph Suarez, Justin Johnson, Fei-Fei Li
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel Dynamic Differentiable Reasoning (DDR) framework for jointly learning branching programs and the functions composing them; this resolves a significant nondifferentiability inhibiting recent dynamic architectures. We apply our framework to two settings in two highly compact and data efficient architectures: DDRprog for CLEVR Visual Question Answering and DDRstack for reverse Polish notation expression evaluation. DDRprog uses a recurrent controller to jointly predict and execute modular neural programs that directly correspond to the underlying question logic; it explicitly forks subprocesses to handle logical branching. By effectively leveraging additional structural supervision, we achieve a large improvement over previous approaches in subtask consistency and a small improvement in overall accuracy. We further demonstrate the benefits of structural supervision in the RPN setting: the inclusion of a stack assumption in DDRstack allows our approach to generalize to long expressions where an LSTM fails the task.

##### Abstract (translated by Google)
我们提出了一个新颖的动态差分推理（DDR）框架，用于联合学习分支程序和组成它们的函数;这解决了显着的不可区分性，抑制了最近的动态架构。我们将这个框架应用于两个高度紧凑和数据高效的体系结构中的两个设置：用于CLEVR Visual Question Answering的DDRprog和用于反转波兰表示法评估的DDRstack。 DDRprog使用循环控制器来联合预测和执行模块化的神经程序，这些程序直接对应于潜在的问题逻辑;它明确地分派子进程来处理逻辑分支。通过有效利用额外的结构监督，我们在子任务一致性方面比以前的方法有了很大的改进，总体精确度有了小的改进。我们进一步证明了结构监督在RPN设置中的好处：在DDRstack中包含堆栈假设允许我们的方法推广到LSTM未能完成任务的长表达式。

##### URL
[https://arxiv.org/abs/1803.11361](https://arxiv.org/abs/1803.11361)

##### PDF
[https://arxiv.org/pdf/1803.11361](https://arxiv.org/pdf/1803.11361)

