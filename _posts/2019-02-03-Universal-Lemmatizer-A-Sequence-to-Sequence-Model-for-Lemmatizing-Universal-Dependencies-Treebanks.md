---
layout: post
title: "Universal Lemmatizer: A Sequence to Sequence Model for Lemmatizing Universal Dependencies Treebanks"
date: 2019-02-03 21:38:29
categories: arXiv_CL
tags: arXiv_CL Sparse Face
author: Jenna Kanerva, Filip Ginter, Tapio Salakoski
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we present a novel lemmatization method based on a sequence-to-sequence neural network architecture and morphosyntactic context representation. In the proposed method, our context-sensitive lemmatizer generates the lemma one character at a time based on the surface form characters and its morphosyntactic features obtained from a morphological tagger. We argue that a sliding window context representation suffers from sparseness, while in majority of cases the morphosyntactic features of a word bring enough information to resolve lemma ambiguities while keeping the context representation dense and more practical for machine learning systems. Additionally, we study two different data augmentation methods utilizing autoencoder training and morphological transducers especially beneficial for low resource languages. We evaluate our lemmatizer on 52 different languages and 76 different treebanks, showing that our system outperforms all latest baseline systems. Compared to the best overall baseline, UDPipe Future, our system outperforms it on 60 out of 76 treebanks reducing errors on average by 18% relative. The lemmatizer together with all trained models is made available as a part of the Turku-neural-parsing-pipeline under the Apache 2.0 license.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.00972](http://arxiv.org/abs/1902.00972)

##### PDF
[http://arxiv.org/pdf/1902.00972](http://arxiv.org/pdf/1902.00972)

