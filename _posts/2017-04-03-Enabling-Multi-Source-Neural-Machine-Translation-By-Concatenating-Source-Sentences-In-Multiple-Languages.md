---
layout: post
title: 'Enabling Multi-Source Neural Machine Translation By Concatenating Source Sentences In Multiple Languages'
date: 2017-04-03 11:37:41
categories: arXiv_CL
tags: arXiv_CL GAN NMT
author: Raj Dabre, Fabien Cromieres, Sadao Kurohashi
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel and elegant solution to "Multi-Source Neural Machine Translation" (MSNMT) which only relies on preprocessing a N-way multilingual corpus without modifying the Neural Machine Translation (NMT) architecture or training procedure. We simply concatenate the source sentences to form a single long multi-source input sentence while keeping the target side sentence as it is and train an NMT system using this preprocessed corpus. We evaluate our method in resource poor as well as resource rich settings and show its effectiveness (up to 4 BLEU using 2 source languages and up to 6 BLEU using 5 source languages) by comparing against existing methods for MSNMT. We also provide some insights on how the NMT system leverages multilingual information in such a scenario by visualizing attention.

##### Abstract (translated by Google)
本文针对“多源神经机器翻译”（MSNMT）提出了一种新颖而精美的解决方案，它只依赖对N-way多语种语料进行预处理，而不需要修改神经机器翻译（NMT）架构或训练过程。我们简单地连接源句子，形成一个长的多源输入句子，同时保持目标句子，并使用这个预处理的语料库训练一个NMT系统。我们通过与MSNMT的现有方法进行比较，评估我们在资源不足以及资源丰富的环境中的方法，并显示其有效性（使用两种源语言最多4个BLEU，使用5种源语言最多6个BLEU）。我们还提供一些关于NMT系统如何通过可视化注意力在这种情况下利用多语言信息的见解。

##### URL
[https://arxiv.org/abs/1702.06135](https://arxiv.org/abs/1702.06135)

