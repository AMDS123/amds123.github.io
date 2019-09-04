---
layout: post
title: "Explicit Cross-lingual Pre-training for Unsupervised Machine Translation"
date: 2019-08-31 09:58:57
categories: arXiv_CL
tags: arXiv_CL Embedding Language_Model
author: Shuo Ren, Yu Wu, Shujie Liu, Ming Zhou, Shuai Ma
mathjax: true
---

* content
{:toc}

##### Abstract
Pre-training has proven to be effective in unsupervised machine translation due to its ability to model deep context information in cross-lingual scenarios. However, the cross-lingual information obtained from shared BPE spaces is inexplicit and limited. In this paper, we propose a novel cross-lingual pre-training method for unsupervised machine translation by incorporating explicit cross-lingual training signals. Specifically, we first calculate cross-lingual n-gram embeddings and infer an n-gram translation table from them. With those n-gram translation pairs, we propose a new pre-training model called Cross-lingual Masked Language Model (CMLM), which randomly chooses source n-grams in the input text stream and predicts their translation candidates at each time step. Experiments show that our method can incorporate beneficial cross-lingual information into pre-trained models. Taking pre-trained CMLM models as the encoder and decoder, we significantly improve the performance of unsupervised machine translation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.00180](http://arxiv.org/abs/1909.00180)

##### PDF
[http://arxiv.org/pdf/1909.00180](http://arxiv.org/pdf/1909.00180)

