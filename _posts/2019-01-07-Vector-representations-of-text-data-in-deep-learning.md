---
layout: post
title: "Vector representations of text data in deep learning"
date: 2019-01-07 08:03:35
categories: arXiv_CL
tags: arXiv_CL GAN Embedding Transfer_Learning Deep_Learning Quantitative Relation
author: Karol Grzegorczyk
mathjax: true
---

* content
{:toc}

##### Abstract
In this dissertation we report results of our research on dense distributed representations of text data. We propose two novel neural models for learning such representations. The first model learns representations at the document level, while the second model learns word-level representations. 
 For document-level representations we propose Binary Paragraph Vector: a neural network models for learning binary representations of text documents, which can be used for fast document retrieval. We provide a thorough evaluation of these models and demonstrate that they outperform the seminal method in the field in the information retrieval task. We also report strong results in transfer learning settings, where our models are trained on a generic text corpus and then used to infer codes for documents from a domain-specific dataset. In contrast to previously proposed approaches, Binary Paragraph Vector models learn embeddings directly from raw text data. 
 For word-level representations we propose Disambiguated Skip-gram: a neural network model for learning multi-sense word embeddings. Representations learned by this model can be used in downstream tasks, like part-of-speech tagging or identification of semantic relations. In the word sense induction task Disambiguated Skip-gram outperforms state-of-the-art models on three out of four benchmarks datasets. Our model has an elegant probabilistic interpretation. Furthermore, unlike previous models of this kind, it is differentiable with respect to all its parameters and can be trained with backpropagation. In addition to quantitative results, we present qualitative evaluation of Disambiguated Skip-gram, including two-dimensional visualisations of selected word-sense embeddings.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.01695](http://arxiv.org/abs/1901.01695)

##### PDF
[http://arxiv.org/pdf/1901.01695](http://arxiv.org/pdf/1901.01695)

