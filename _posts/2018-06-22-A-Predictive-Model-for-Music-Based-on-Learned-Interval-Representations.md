---
layout: post
title: "A Predictive Model for Music Based on Learned Interval Representations"
date: 2018-06-22 14:17:04
categories: arXiv_AI
tags: arXiv_AI RNN
author: Stefan Lattner, Maarten Grachten, Gerhard Widmer
mathjax: true
---

* content
{:toc}

##### Abstract
Connectionist sequence models (e.g., RNNs) applied to musical sequences suffer from two known problems: First, they have strictly "absolute pitch perception". Therefore, they fail to generalize over musical concepts which are commonly perceived in terms of relative distances between pitches (e.g., melodies, scale types, modes, cadences, or chord types). Second, they fall short of capturing the concepts of repetition and musical form. In this paper we introduce the recurrent gated autoencoder (RGAE), a recurrent neural network which learns and operates on interval representations of musical sequences. The relative pitch modeling increases generalization and reduces sparsity in the input data. Furthermore, it can learn sequences of copy-and-shift operations (i.e. chromatically transposed copies of musical fragments)---a promising capability for learning musical repetition structure. We show that the RGAE improves the state of the art for general connectionist sequence models in learning to predict monophonic melodies, and that ensembles of relative and absolute music processing models improve the results appreciably. Furthermore, we show that the relative pitch processing of the RGAE naturally facilitates the learning and the generation of sequences of copy-and-shift operations, wherefore the RGAE greatly outperforms a common absolute pitch recurrent neural network on this task.

##### Abstract (translated by Google)
应用于音乐序列的连接主义序列模型（例如，RNN）遭受两个已知问题：首先，它们严格地具有“绝对音调感知”。因此，它们不能概括通常根据音高之间的相对距离（例如，旋律，音阶类型，模式，节奏或和弦类型）而感知的音乐概念。其次，他们没有抓住重复和音乐形式的概念。在本文中，我们介绍经常性门控自动编码器（RGAE），它是一种循环式神经网络，学习和操作音乐序列的间隔表示。相对音高建模增加了泛化并降低了输入数据的稀疏性。此外，它还可以学习复制和移位操作的顺序（即音乐片段的色调转置副本）---一种有前途的学习音乐重复结构的能力。我们展示了RGAE改进了一般连接序列模型在学习预测单音旋律方面的艺术状态，并且相对和绝对音乐处理模型的合奏显着提高了结果。此外，我们证明RGAE的相对音高处理自然便于学习和复制和移位操作序列的生成，因此RGAE在这项任务上远远优于共同的绝对音调递归神经网络。

##### URL
[http://arxiv.org/abs/1806.08686](http://arxiv.org/abs/1806.08686)

##### PDF
[http://arxiv.org/pdf/1806.08686](http://arxiv.org/pdf/1806.08686)

