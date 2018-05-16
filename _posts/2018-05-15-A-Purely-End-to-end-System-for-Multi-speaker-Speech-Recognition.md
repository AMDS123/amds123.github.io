---
layout: post
title: "A Purely End-to-end System for Multi-speaker Speech Recognition"
date: 2018-05-15 14:45:33
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Recognition
author: Hiroshi Seki, Takaaki Hori, Shinji Watanabe, Jonathan Le Roux, John R. Hershey
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, there has been growing interest in multi-speaker speech recognition, where the utterances of multiple speakers are recognized from their mixture. Promising techniques have been proposed for this task, but earlier works have required additional training data such as isolated source signals or senone alignments for effective learning. In this paper, we propose a new sequence-to-sequence framework to directly decode multiple label sequences from a single speech sequence by unifying source separation and speech recognition functions in an end-to-end manner. We further propose a new objective function to improve the contrast between the hidden vectors to avoid generating similar hypotheses. Experimental results show that the model is directly able to learn a mapping from a speech mixture to multiple label sequences, achieving 83.1 % relative improvement compared to a model trained without the proposed objective. Interestingly, the results are comparable to those produced by previous end-to-end works featuring explicit separation and recognition modules.

##### Abstract (translated by Google)
最近，人们越来越关注多说话人语音识别，其中多个说话人的话语从他们的混合物中被识别出来。已经提出了有希望的技术来完成这项任务，但是早期的工作需要额外的训练数据，如孤立的源信号或者用于有效学习的语音对齐。在本文中，我们提出了一个新的序列到序列框架，通过统一源分离和语音识别功能，以一种单一的语音序列以端到端的方式直接解码多个标签序列。我们进一步提出了一种新的目标函数来改善隐藏向量之间的对比以避免产生类似的假设。实验结果表明，该模型直接能够学习从语音混合到多个标签序列的映射，与没有提出目标训练的模型相比，实现了83.1％的相对改进。有趣的是，这些结果与以前具有明确分离和识别模块的端到端作品所产生的结果相当。

##### URL
[http://arxiv.org/abs/1805.05826](http://arxiv.org/abs/1805.05826)

##### PDF
[http://arxiv.org/pdf/1805.05826](http://arxiv.org/pdf/1805.05826)

