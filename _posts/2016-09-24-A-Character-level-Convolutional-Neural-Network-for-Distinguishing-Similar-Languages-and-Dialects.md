---
layout: post
title: "A Character-level Convolutional Neural Network for Distinguishing Similar Languages and Dialects"
date: 2016-09-24 04:02:13
categories: arXiv_CL
tags: arXiv_CL Face CNN
author: Yonatan Belinkov, James Glass
mathjax: true
---

* content
{:toc}

##### Abstract
Discriminating between closely-related language varieties is considered a challenging and important task. This paper describes our submission to the DSL 2016 shared-task, which included two sub-tasks: one on discriminating similar languages and one on identifying Arabic dialects. We developed a character-level neural network for this task. Given a sequence of characters, our model embeds each character in vector space, runs the sequence through multiple convolutions with different filter widths, and pools the convolutional representations to obtain a hidden vector representation of the text that is used for predicting the language or dialect. We primarily focused on the Arabic dialect identification task and obtained an F1 score of 0.4834, ranking 6th out of 18 participants. We also analyze errors made by our system on the Arabic data in some detail, and point to challenges such an approach is faced with.

##### Abstract (translated by Google)
辨别密切相关的语言品种被认为是一项具有挑战性的重要任务。本文介绍了我们提交给DSL 2016共享任务的内容，其中包括两个子任务：一个区分类似语言，一个区分阿拉伯语方言。我们为这个任务开发了一个字符级的神经网络。给定一个字符序列，我们的模型将每个字符嵌入到向量空间中，通过具有不同滤波器宽度的多个卷积来运行序列，并汇集卷积表示以获得用于预测语言或方言的文本的隐藏向量表示。我们主要关注阿拉伯语方言识别任务，获得了0.4834的F1分数，在18名参与者中排名第六。我们还详细分析了我们的系统对阿拉伯数据所犯的错误，并指出了这种方法面临的挑战。

##### URL
[https://arxiv.org/abs/1609.07568](https://arxiv.org/abs/1609.07568)

##### PDF
[https://arxiv.org/pdf/1609.07568](https://arxiv.org/pdf/1609.07568)

