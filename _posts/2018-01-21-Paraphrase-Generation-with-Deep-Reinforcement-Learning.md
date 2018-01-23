---
layout: post
title: "Paraphrase Generation with Deep Reinforcement Learning"
date: 2018-01-21 06:29:23
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
从给定的句子中自动生成释义是自然语言处理（NLP）中一个重要而又具有挑战性的任务，在许多应用如回答问题，搜索和对话中起着关键作用。在本文中，我们提出了一个深层次的强化学习方法来解释生成。具体来说，我们提出了一个新的任务框架，它由一个\ textit {generator}和一个\ textit {评估者}组成，两者都是从数据中学习的。作为序列到序列的学习模型构建的生成器可以给出一个句子的释义。作为一个深度匹配模型的评估者可以判断两个句子是否是彼此的解释。生成器首先通过深度学习进行训练，然后通过强化学习进一步进行微调，评估者给予奖励。对于评估者的学习，根据可用训练数据的类型，我们分别提出了两种基于监督学习和反强化学习的方法。实证研究表明，学习的评估者可以指导发生器产生更准确的释义。实验结果表明，所提出的模型（发生器）在自动评估和人工评估中优于最新的解释生成方法。

##### URL
[http://arxiv.org/abs/1711.00279](http://arxiv.org/abs/1711.00279)

##### PDF
[http://arxiv.org/pdf/1711.00279](http://arxiv.org/pdf/1711.00279)

