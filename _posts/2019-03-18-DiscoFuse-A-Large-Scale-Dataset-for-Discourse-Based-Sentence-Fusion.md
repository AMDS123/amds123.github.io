---
layout: post
title: "DiscoFuse: A Large-Scale Dataset for Discourse-Based Sentence Fusion"
date: 2019-03-18 12:27:53
categories: arXiv_CL
tags: arXiv_CL Transfer_Learning
author: Mor Geva, Eric Malmi, Idan Szpektor, Jonathan Berant
mathjax: true
---

* content
{:toc}

##### Abstract
Sentence fusion is the task of joining several independent sentences into a single coherent text. Current datasets for sentence fusion are small and insufficient for training modern neural models. In this paper, we propose a method for automatically-generating fusion examples from raw text and present DiscoFuse, a large scale dataset for discourse-based sentence fusion. We author a set of rules for identifying a diverse set of discourse phenomena in raw text, and decomposing the text into two independent sentences. We apply our approach on two document collections: Wikipedia and Sports articles, yielding 60 million fusion examples annotated with discourse information required to reconstruct the fused text. We develop a sequence-to-sequence model on DiscoFuse and thoroughly analyze its strengths and weaknesses with respect to the various discourse phenomena, using both automatic as well as human evaluation. Finally, we conduct transfer learning experiments with WebSplit, a recent dataset for text simplification. We show that pretraining on DiscoFuse substantially improves performance on WebSplit when viewed as a sentence fusion task.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.10526](http://arxiv.org/abs/1902.10526)

##### PDF
[http://arxiv.org/pdf/1902.10526](http://arxiv.org/pdf/1902.10526)

