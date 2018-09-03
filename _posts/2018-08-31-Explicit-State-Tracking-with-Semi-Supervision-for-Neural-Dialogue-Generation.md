---
layout: post
title: "Explicit State Tracking with Semi-Supervision for Neural Dialogue Generation"
date: 2018-08-31 04:27:41
categories: arXiv_CL
tags: arXiv_CL Regularization Tracking
author: Xisen Jin, Wenqiang Lei, Zhaochun Ren, Hongshen Chen, Shangsong Liang, Yihong Zhao, Dawei Yin
mathjax: true
---

* content
{:toc}

##### Abstract
The task of dialogue generation aims to automatically provide responses given previous utterances. Tracking dialogue states is an important ingredient in dialogue generation for estimating users' intention. However, the \emph{expensive nature of state labeling} and the \emph{weak interpretability} make the dialogue state tracking a challenging problem for both task-oriented and non-task-oriented dialogue generation: For generating responses in task-oriented dialogues, state tracking is usually learned from manually annotated corpora, where the human annotation is expensive for training; for generating responses in non-task-oriented dialogues, most of existing work neglects the explicit state tracking due to the unlimited number of dialogue states. 
 In this paper, we propose the \emph{semi-supervised explicit dialogue state tracker} (SEDST) for neural dialogue generation. To this end, our approach has two core ingredients: \emph{CopyFlowNet} and \emph{posterior regularization}. Specifically, we propose an encoder-decoder architecture, named \emph{CopyFlowNet}, to represent an explicit dialogue state with a probabilistic distribution over the vocabulary space. To optimize the training procedure, we apply a posterior regularization strategy to integrate indirect supervision. Extensive experiments conducted on both task-oriented and non-task-oriented dialogue corpora demonstrate the effectiveness of our proposed model. Moreover, we find that our proposed semi-supervised dialogue state tracker achieves a comparable performance as state-of-the-art supervised learning baselines in state tracking procedure.

##### Abstract (translated by Google)
对话生成的任务旨在自动提供先前发表的回应。跟踪对话状态是用于估计用户意图的对话生成的重要因素。然而，\ emph {国家标签的昂贵性质}和\ emph {弱解释性}使对话状态跟踪成为面向任务和非面向任务的对话生成的一个具有挑战性的问题：用于在面向任务的对话中生成响应，状态跟踪通常是从手动注释的语料库中学习的，其中人类注释对于训练是昂贵的;为了在非面向任务的对话中产生响应，由于无限数量的对话状态，大多数现有工作忽略了显式状态跟踪。
 在本文中，我们提出了用于神经对话生成的\ emph {半监督明确对话状态跟踪器}（SEDST）。为此，我们的方法有两个核心要素：\ emph {CopyFlowNet}和\ emph {后验正则化}。具体来说，我们提出了一种名为\ emph {CopyFlowNet}的编码器 - 解码器架构，用于表示在词汇空间上具有概率分布的显式对话状态。为了优化培训程序，我们采用后验正则化策略来整合间接监督。在面向任务和非任务导向的对话语料库上进行的大量实验证明了我们提出的模型的有效性。此外，我们发现我们提出的半监督对话状态跟踪器实现了与状态跟踪程序中最先进的监督学习基线相当的性能。

##### URL
[http://arxiv.org/abs/1808.10596](http://arxiv.org/abs/1808.10596)

##### PDF
[http://arxiv.org/pdf/1808.10596](http://arxiv.org/pdf/1808.10596)

