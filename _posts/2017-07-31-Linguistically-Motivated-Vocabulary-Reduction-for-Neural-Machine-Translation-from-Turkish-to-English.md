---
layout: post
title: "Linguistically Motivated Vocabulary Reduction for Neural Machine Translation from Turkish to English"
date: 2017-07-31 14:31:01
categories: arXiv_CL
tags: arXiv_CL Segmentation NMT
author: Duygu Ataman, Matteo Negri, Marco Turchi, Marcello Federico
mathjax: true
---

* content
{:toc}

##### Abstract
The necessity of using a fixed-size word vocabulary in order to control the model complexity in state-of-the-art neural machine translation (NMT) systems is an important bottleneck on performance, especially for morphologically rich languages. Conventional methods that aim to overcome this problem by using sub-word or character-level representations solely rely on statistics and disregard the linguistic properties of words, which leads to interruptions in the word structure and causes semantic and syntactic losses. In this paper, we propose a new vocabulary reduction method for NMT, which can reduce the vocabulary of a given input corpus at any rate while also considering the morphological properties of the language. Our method is based on unsupervised morphology learning and can be, in principle, used for pre-processing any language pair. We also present an alternative word segmentation method based on supervised morphological analysis, which aids us in measuring the accuracy of our model. We evaluate our method in Turkish-to-English NMT task where the input language is morphologically rich and agglutinative. We analyze different representation methods in terms of translation accuracy as well as the semantic and syntactic properties of the generated output. Our method obtains a significant improvement of 2.3 BLEU points over the conventional vocabulary reduction technique, showing that it can provide better accuracy in open vocabulary translation of morphologically rich languages.

##### Abstract (translated by Google)
为了在现有技术的神经机器翻译（NMT）系统中使用固定大小的词汇词汇来控制模型复杂性的必要性是性能上的一个重要瓶颈，尤其是在形态丰富的语言中。旨在通过使用子词或字符级表示来克服这个问题的传统方法完全依赖于统计学并且忽略了词的语言特性，这导致词结构的中断，并导致语义和句法损失。在本文中，我们提出了一种新的NMT的词汇缩减方法，它可以在任何速度下减少给定输入语料库的词汇量，同时也考虑语言的形态特征。我们的方法基于无监督形态学习，原则上可用于预处理任何语言对。我们还提出了一种基于监督形态分析的备选分词方法，帮助我们测量模型的准确性。我们评估我们的方法在土耳其语到英语的NMT任务，其中输入语言是形态丰富和凝集。我们从翻译的准确性以及生成的输出的语义和语法特性来分析不同的表示方法。与传统的词汇量缩减技术相比，我们的方法获得了2.3 BLEU点的显着提高，表明它可以在形态丰富的语言的开放词汇翻译中提供更好的准确性。

##### URL
[https://arxiv.org/abs/1707.09879](https://arxiv.org/abs/1707.09879)

