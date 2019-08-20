---
layout: post
title: "Understanding Undesirable Word Embedding Associations"
date: 2019-08-18 01:28:45
categories: arXiv_CL
tags: arXiv_CL Embedding Relation
author: Kawin Ethayarajh, David Duvenaud, Graeme Hirst
mathjax: true
---

* content
{:toc}

##### Abstract
Word embeddings are often criticized for capturing undesirable word associations such as gender stereotypes. However, methods for measuring and removing such biases remain poorly understood. We show that for any embedding model that implicitly does matrix factorization, debiasing vectors post hoc using subspace projection (Bolukbasi et al., 2016) is, under certain conditions, equivalent to training on an unbiased corpus. We also prove that WEAT, the most common association test for word embeddings, systematically overestimates bias. Given that the subspace projection method is provably effective, we use it to derive a new measure of association called the $\textit{relational inner product association}$ (RIPA). Experiments with RIPA reveal that, on average, skipgram with negative sampling (SGNS) does not make most words any more gendered than they are in the training corpus. However, for gender-stereotyped words, SGNS actually amplifies the gender association in the corpus.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.06361](http://arxiv.org/abs/1908.06361)

##### PDF
[http://arxiv.org/pdf/1908.06361](http://arxiv.org/pdf/1908.06361)

