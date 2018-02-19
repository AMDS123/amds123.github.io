---
layout: post
title: "Structured-based Curriculum Learning for End-to-end English-Japanese Speech Translation"
date: 2018-02-13 11:33:27
categories: arXiv_SD
tags: arXiv_SD Attention Speech_Recognition Recognition
author: Takatomo Kano, Sakriani Sakti, Satoshi Nakamura
mathjax: true
---

* content
{:toc}

##### Abstract
Sequence-to-sequence attentional-based neural network architectures have been shown to provide a powerful model for machine translation and speech recognition. Recently, several works have attempted to extend the models for end-to-end speech translation task. However, the usefulness of these models were only investigated on language pairs with similar syntax and word order (e.g., English-French or English-Spanish). In this work, we focus on end-to-end speech translation tasks on syntactically distant language pairs (e.g., English-Japanese) that require distant word reordering. 
 To guide the encoder-decoder attentional model to learn this difficult problem, we propose a structured-based curriculum learning strategy. 
 Unlike conventional curriculum learning that gradually emphasizes difficult data examples, we formalize learning strategies from easier network structures to more difficult network structures. Here, we start the training with end-to-end encoder-decoder for speech recognition or text-based machine translation task then gradually move to end-to-end speech translation task. The experiment results show that the proposed approach could provide significant improvements in comparison with the one without curriculum learning.

##### Abstract (translated by Google)
已经证明，基于序列注意的神经网络体系结构为机器翻译和语音识别提供了强大的模型。最近，一些作品试图扩展端到端语音翻译任务的模型。然而，这些模型的有用性仅在具有相似语法和词序的语言对（例如英语 - 法语或英语 - 西班牙语）上进行调查。在这项工作中，我们将重点放在语法遥远的语言对（例如英语 - 日语）上需要远距离重新排序的端到端语音翻译任务。
 为了引导编码器 - 解码器的注意模型来学习这个难题，我们提出了一种基于结构的课程学习策略。
 与逐渐强调困难数据示例的传统课程学习不同，我们将学习策略从更简单的网络结构形式化为更困难的网络结构。在这里，我们开始使用端到端编码器 - 解码器进行语音识别或基于文本的机器翻译任务的训练，然后逐渐转向端到端语音翻译任务。实验结果表明，与没有课程学习的方法相比，所提出的方法可以提供显着的改进。

##### URL
[http://arxiv.org/abs/1802.06003](http://arxiv.org/abs/1802.06003)

##### PDF
[http://arxiv.org/pdf/1802.06003](http://arxiv.org/pdf/1802.06003)

