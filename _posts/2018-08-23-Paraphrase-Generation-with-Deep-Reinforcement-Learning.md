---
layout: post
title: "Paraphrase Generation with Deep Reinforcement Learning"
date: 2018-08-23 09:30:33
categories: arXiv_CL
tags: arXiv_CL Reinforcement_Learning Deep_Learning
author: Zichao Li, Xin Jiang, Lifeng Shang, Hang Li
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic generation of paraphrases from a given sentence is an important yet challenging task in natural language processing (NLP), and plays a key role in a number of applications such as question answering, search, and dialogue. In this paper, we present a deep reinforcement learning approach to paraphrase generation. Specifically, we propose a new framework for the task, which consists of a \textit{generator} and an \textit{evaluator}, both of which are learned from data. The generator, built as a sequence-to-sequence learning model, can produce paraphrases given a sentence. The evaluator, constructed as a deep matching model, can judge whether two sentences are paraphrases of each other. The generator is first trained by deep learning and then further fine-tuned by reinforcement learning in which the reward is given by the evaluator. For the learning of the evaluator, we propose two methods based on supervised learning and inverse reinforcement learning respectively, depending on the type of available training data. Empirical study shows that the learned evaluator can guide the generator to produce more accurate paraphrases. Experimental results demonstrate the proposed models (the generators) outperform the state-of-the-art methods in paraphrase generation in both automatic evaluation and human evaluation.

##### Abstract (translated by Google)
从给定句子自动生成释义是自然语言处理（NLP）中的一项重要且具有挑战性的任务，并且在诸如问答，搜索和对话的许多应用中起关键作用。在本文中，我们提出了一种深层强化学习方法来解释生成。具体来说，我们提出了一个新的任务框架，它由一个\ textit {generator}和一个\ textit {evaluateator}组成，这两个框架都是从数据中学习的。作为序列到序列学习模型构建的生成器可以产生给出句子的释义。构造为深度匹配模型的评估者可以判断两个句子是否相互解释。首先通过深度学习训练发生器，然后通过强化学习进一步微调，其中奖励由评估者给出。为了学习评估者，我们根据可用的训练数据的类型分别提出了两种基于监督学习和逆强化学习的方法。实证研究表明，学习评估者可以指导发电机产生更准确的释义。实验结果表明，在自动评估和人工评估中，所提出的模型（发生器）在复述生成方面优于最先进的方法。

##### URL
[http://arxiv.org/abs/1711.00279](http://arxiv.org/abs/1711.00279)

##### PDF
[http://arxiv.org/pdf/1711.00279](http://arxiv.org/pdf/1711.00279)

