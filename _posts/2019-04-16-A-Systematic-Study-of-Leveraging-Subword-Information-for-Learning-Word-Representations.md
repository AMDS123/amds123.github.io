---
layout: post
title: "A Systematic Study of Leveraging Subword Information for Learning Word Representations"
date: 2019-04-16 21:50:32
categories: arXiv_CL
tags: arXiv_CL Segmentation Attention Embedding Represenation_Learning
author: Yi Zhu, Ivan Vuli&#x107;, Anna Korhonen
mathjax: true
---

* content
{:toc}

##### Abstract
The use of subword-level information (e.g., characters, character n-grams, morphemes) has become ubiquitous in modern word representation learning. Its importance is attested especially for morphologically rich languages which generate a large number of rare words. Despite a steadily increasing interest in such subword-informed word representations, their systematic comparative analysis across typologically diverse languages and different tasks is still missing. In this work, we deliver such a study focusing on the variation of two crucial components required for subword-level integration into word representation models: 1) segmentation of words into subword units, and 2) subword composition functions to obtain final word representations. We propose a general framework for learning subword-informed word representations that allows for easy experimentation with different segmentation and composition components, also including more advanced techniques based on position embeddings and self-attention. Using the unified framework, we run experiments over a large number of subword-informed word representation configurations (60 in total) on 3 tasks (general and rare word similarity, dependency parsing, fine-grained entity typing) for 5 languages representing 3 language types. Our main results clearly indicate that there is no "one-sizefits-all" configuration, as performance is both language- and task-dependent. We also show that configurations based on unsupervised segmentation (e.g., BPE, Morfessor) are sometimes comparable to or even outperform the ones based on supervised word segmentation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.07994](http://arxiv.org/abs/1904.07994)

##### PDF
[http://arxiv.org/pdf/1904.07994](http://arxiv.org/pdf/1904.07994)

