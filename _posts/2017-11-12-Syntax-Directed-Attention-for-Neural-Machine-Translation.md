---
layout: post
title: "Syntax-Directed Attention for Neural Machine Translation"
date: 2017-11-12 03:35:48
categories: arXiv_CL
tags: arXiv_CL Attention NMT Prediction
author: Kehai Chen, Rui Wang, Masao Utiyama, Eiichiro Sumita, Tiejun Zhao
mathjax: true
---

* content
{:toc}

##### Abstract
Attention mechanism, including global attention and local attention, plays a key role in neural machine translation (NMT). Global attention attends to all source words for word prediction. In comparison, local attention selectively looks at fixed-window source words. However, alignment weights for the current target word often decrease to the left and right by linear distance centering on the aligned source position and neglect syntax-directed distance constraints. In this paper, we extend local attention with syntax-distance constraint, to focus on syntactically related source words with the predicted target word, thus learning a more effective context vector for word prediction. Moreover, we further propose a double context NMT architecture, which consists of a global context vector and a syntax-directed context vector over the global attention, to provide more translation performance for NMT from source representation. The experiments on the large-scale Chinese-to-English and English-to-Germen translation tasks show that the proposed approach achieves a substantial and significant improvement over the baseline system.

##### Abstract (translated by Google)
注意机制，包括全球关注和局部关注，在神经机器翻译（NMT）中起着关键作用。全球的注意力都集中在所有的单词预测的源词上。相比之下，本地的注意力选择性地看固定窗口源词。然而，当前目标词的对齐权重通常以对齐的源位置为中心的线性距离向左和向右递减，并且忽略了语法引导的距离约束。在本文中，我们通过句法 - 距离约束来扩展局部注意力，将注意力集中在与预测的目标词汇相关的句子相关的源词汇上，从而为词汇预测学习更有效的上下文向量。此外，我们进一步提出了一个双上下文NMT体系结构，它包括一个全局上下文向量和一个全局关注的句法向上的上下文向量，以从源表示为NMT提供更多的翻译性能。大规模的中英文和英文到德文翻译任务的实验表明，所提出的方法实现了比基准系统有显着的和显着的改进。

##### URL
[https://arxiv.org/abs/1711.04231](https://arxiv.org/abs/1711.04231)

##### PDF
[https://arxiv.org/pdf/1711.04231](https://arxiv.org/pdf/1711.04231)

