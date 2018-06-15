---
layout: post
title: "Morphological and Language-Agnostic Word Segmentation for NMT"
date: 2018-06-14 11:44:48
categories: arXiv_CL
tags: arXiv_CL Segmentation NMT
author: Dominik Mach&#xe1;&#x10d;ek, Jon&#xe1;&#x161; Vidra, Ond&#x159;ej Bojar
mathjax: true
---

* content
{:toc}

##### Abstract
The state of the art of handling rich morphology in neural machine translation (NMT) is to break word forms into subword units, so that the overall vocabulary size of these units fits the practical limits given by the NMT model and GPU memory capacity. In this paper, we compare two common but linguistically uninformed methods of subword construction (BPE and STE, the method implemented in Tensor2Tensor toolkit) and two linguistically-motivated methods: Morfessor and one novel method, based on a derivational dictionary. Our experiments with German-to-Czech translation, both morphologically rich, document that so far, the non-motivated methods perform better. Furthermore, we iden- tify a critical difference between BPE and STE and show a simple pre- processing step for BPE that considerably increases translation quality as evaluated by automatic measures.

##### Abstract (translated by Google)
在神经机器翻译（NMT）中处理丰富形态学的技术状态是将单词形式分解为子字单元，以使这些单元的总体词汇量大小符合由NMT模型和GPU存储器容量给出的实际限制。在本文中，我们比较了两种常见但语言学上不知情的子词构造方法（BPE和STE，在Tensor2Tensor工具包中实现的方法）和两种基于语言动机的方法：Morfessor和一种基于派生词典的新颖方法。我们的德语译成捷克语的实验，形态丰富，记录到目前为止，无动机的方法表现更好。此外，我们确定了BPE和STE之间的关键区别，并展示了一个BPE的简单预处理步骤，通过自动测量评估，显着提高翻译质量。

##### URL
[http://arxiv.org/abs/1806.05482](http://arxiv.org/abs/1806.05482)

##### PDF
[http://arxiv.org/pdf/1806.05482](http://arxiv.org/pdf/1806.05482)

