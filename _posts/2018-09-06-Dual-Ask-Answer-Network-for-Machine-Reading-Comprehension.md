---
layout: post
title: "Dual Ask-Answer Network for Machine Reading Comprehension"
date: 2018-09-06 13:57:03
categories: arXiv_AI
tags: arXiv_AI Knowledge Attention
author: Han Xiao, Feng Wang, Yanjian Feng, Jingyao Zheng
mathjax: true
---

* content
{:toc}

##### Abstract
There are three modalities in the reading comprehension setting: question, answer and context. The task of question answering or question generation aims to infer an answer or a question when given the counterpart based on context. We present a novel two-way neural sequence transduction model that connects three modalities, allowing it to learn two tasks simultaneously and mutually benefit one another. During training, the model receives question-context-answer triplets as input and captures the cross-modal interaction via a hierarchical attention process. Unlike previous joint learning paradigms that leverage the duality of question generation and question answering at data level, we solve such dual tasks at the architecture level by mirroring the network structure and partially sharing components at different layers. This enables the knowledge to be transferred from one task to another, helping the model to find a general representation for each modality. The evaluation on four public datasets shows that our dual-learning model outperforms the mono-learning counterpart as well as the state-of-the-art joint models on both question answering and question generation tasks.

##### Abstract (translated by Google)
阅读理解设置有三种形式：问题，答案和背景。问答或问题生成的任务旨在根据上下文给出对方的答案或问题。我们提出了一种新的双向神经序列转导模型，它连接三种方式，使其能够同时学习两个任务，并相互互利。在训练期间，模型接收问题 - 上下文 - 答案三元组作为输入，并通过分层注意过程捕获跨模态交互。与以前利用数据级问题生成和问答的二元性的联合学习范式不同，我们通过镜像网络结构和部分共享不同层的组件来在架构级解决这样的双重任务。这使得知识可以从一个任务转移到另一个任务，帮助模型找到每种模态的一般表示。对四个公共数据集的评估表明，我们的双学习模型优于单一学习模型以及问答和问题生成任务的最新联合模型。

##### URL
[http://arxiv.org/abs/1809.01997](http://arxiv.org/abs/1809.01997)

##### PDF
[http://arxiv.org/pdf/1809.01997](http://arxiv.org/pdf/1809.01997)

