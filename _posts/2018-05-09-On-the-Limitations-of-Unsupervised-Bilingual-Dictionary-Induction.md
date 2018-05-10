---
layout: post
title: "On the Limitations of Unsupervised Bilingual Dictionary Induction"
date: 2018-05-09 17:08:03
categories: arXiv_CL
tags: arXiv_CL Adversarial Embedding Relation
author: Anders S&#xf8;gaard, Sebastian Ruder, Ivan Vuli&#x107;
mathjax: true
---

* content
{:toc}

##### Abstract
Unsupervised machine translation---i.e., not assuming any cross-lingual supervision signal, whether a dictionary, translations, or comparable corpora---seems impossible, but nevertheless, Lample et al. (2018) recently proposed a fully unsupervised machine translation (MT) model. The model relies heavily on an adversarial, unsupervised alignment of word embedding spaces for bilingual dictionary induction (Conneau et al., 2018), which we examine here. Our results identify the limitations of current unsupervised MT: unsupervised bilingual dictionary induction performs much worse on morphologically rich languages that are not dependent marking, when monolingual corpora from different domains or different embedding algorithms are used. We show that a simple trick, exploiting a weak supervision signal from identical words, enables more robust induction, and establish a near-perfect correlation between unsupervised bilingual dictionary induction performance and a previously unexplored graph similarity metric.

##### Abstract (translated by Google)
无监督机器翻译---即不假设任何跨语言监督信号，不管是字典，翻译还是类似的语料库似乎都是不可能的，但是，Lample等人（2018）最近提出了完全无监督的机器翻译（MT）模型。该模型在很大程度上依赖于敌对的，无监督的用于双语词典诱导的词嵌入空间的对齐（Conneau等，2018），我们在此讨论。我们的结果确定了当前无监督MT的局限性：当使用来自不同领域或不同嵌入算法的单语言语料库时，无监督双语词典归纳对形态学丰富的语言（非依赖性标记）表现更差。我们表明，一个简单的技巧，利用来自相同单词的弱监督信号，可以实现更强大的归纳，并建立无监督双语词典归纳性能和以前未探索的图形相似性度量之间的近乎完美的相关性。

##### URL
[http://arxiv.org/abs/1805.03620](http://arxiv.org/abs/1805.03620)

##### PDF
[http://arxiv.org/pdf/1805.03620](http://arxiv.org/pdf/1805.03620)

