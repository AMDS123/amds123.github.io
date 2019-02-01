---
layout: post
title: "Adding Interpretable Attention to Neural Translation Models Improves Word Alignment"
date: 2019-01-31 14:05:02
categories: arXiv_CL
tags: arXiv_CL Attention Inference Gradient_Descent
author: Thomas Zenkel, Joern Wuebker, John DeNero
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-layer models with multiple attention heads per layer provide superior translation quality compared to simpler and shallower models, but determining what source context is most relevant to each target word is more challenging as a result. Therefore, deriving high-accuracy word alignments from the activations of a state-of-the-art neural machine translation model is an open challenge. We propose a simple model extension to the Transformer architecture that makes use of its hidden representations and is restricted to attend solely on encoder information to predict the next word. It can be trained on bilingual data without word-alignment information. We further introduce a novel alignment inference procedure which applies stochastic gradient descent to directly optimize the attention activations towards a given target word. The resulting alignments dramatically outperform the naive approach to interpreting Transformer attention activations, and are comparable to Giza++ on two publicly available data sets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.11359](http://arxiv.org/abs/1901.11359)

##### PDF
[http://arxiv.org/pdf/1901.11359](http://arxiv.org/pdf/1901.11359)

