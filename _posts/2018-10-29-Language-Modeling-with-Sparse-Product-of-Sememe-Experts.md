---
layout: post
title: "Language Modeling with Sparse Product of Sememe Experts"
date: 2018-10-29 20:13:05
categories: arXiv_CL
tags: arXiv_CL Sparse Language_Model
author: Yihong Gu, Jun Yan, Hao Zhu, Zhiyuan Liu, Ruobing Xie, Maosong Sun, Fen Lin, Leyu Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Most language modeling methods rely on large-scale data to statistically learn the sequential patterns of words. In this paper, we argue that words are atomic language units but not necessarily atomic semantic units. Inspired by HowNet, we use sememes, the minimum semantic units in human languages, to represent the implicit semantics behind words for language modeling, named Sememe-Driven Language Model (SDLM). More specifically, to predict the next word, SDLM first estimates the sememe distribution gave textual context. Afterward, it regards each sememe as a distinct semantic expert, and these experts jointly identify the most probable senses and the corresponding word. In this way, SDLM enables language models to work beyond word-level manipulation to fine-grained sememe-level semantics and offers us more powerful tools to fine-tune language models and improve the interpretability as well as the robustness of language models. Experiments on language modeling and the downstream application of headline gener- ation demonstrate the significant effect of SDLM. Source code and data used in the experiments can be accessed at https:// github.com/thunlp/SDLM-pytorch.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.12387](http://arxiv.org/abs/1810.12387)

##### PDF
[http://arxiv.org/pdf/1810.12387](http://arxiv.org/pdf/1810.12387)

