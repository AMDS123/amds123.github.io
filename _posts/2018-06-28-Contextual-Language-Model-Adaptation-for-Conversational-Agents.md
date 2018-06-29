---
layout: post
title: "Contextual Language Model Adaptation for Conversational Agents"
date: 2018-06-28 05:04:40
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Language_Model Prediction Recognition
author: Anirudh Raju, Behnam Hedayatnia, Linda Liu, Ankur Gandhe, Chandra Khatri, Angeliki Metallinou, Anu Venkatesh, Ariya Rastrow
mathjax: true
---

* content
{:toc}

##### Abstract
Statistical language models (LM) play a key role in Automatic Speech Recognition (ASR) systems used by conversational agents. These ASR systems should provide a high accuracy under a variety of speaking styles, domains, vocabulary and argots. In this paper, we present a DNN-based method to adapt the LM to each user-agent interaction based on generalized contextual information, by predicting an optimal, context-dependent set of LM interpolation weights. We show that this framework for contextual adaptation provides accuracy improvements under different possible mixture LM partitions that are relevant for both (1) Goal-oriented conversational agents where it's natural to partition the data by the requested application and for (2) Non-goal oriented conversational agents where the data can be partitioned using topic labels that come from predictions of a topic classifier. We obtain a relative WER improvement of 3% with a 1-pass decoding strategy and 6% in a 2-pass decoding framework, over an unadapted model. We also show up to a 15% relative improvement in recognizing named entities which is of significant value for conversational ASR systems.

##### Abstract (translated by Google)
统计语言模型（LM）在会话代理使用的自动语音识别（ASR）系统中发挥关键作用。这些ASR系统应该在各种口语风格，领域，词汇和argots下提供高精度。在本文中，我们提出了一种基于DNN的方法，通过预测LM内插权重的最优的，与上下文相关的集合，基于广义上下文信息使LM适应每个用户 - 代理交互。我们发现这种情境适应框架在不同可能的混合LM划分下提供了准确性改进，LM划分与以下两者相关：（1）面向目标的会话代理，根据请求的应用划分数据是自然的;（2）非目标导向可以使用来自主题分类器预测的主题标签对数据进行分区的对话代理。我们通过单通解码策略获得3％的相对WER提高，并且在2通解码框架中获得6％的相对WER提高，而非适应模型。我们还发现在识别命名实体方面相对于对话式ASR系统具有显着价值的15％的相对改进。

##### URL
[https://arxiv.org/abs/1806.10215](https://arxiv.org/abs/1806.10215)

##### PDF
[https://arxiv.org/pdf/1806.10215](https://arxiv.org/pdf/1806.10215)

