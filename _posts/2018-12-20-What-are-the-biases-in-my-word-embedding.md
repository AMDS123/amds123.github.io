---
layout: post
title: "What are the biases in my word embedding?"
date: 2018-12-20 18:53:05
categories: arXiv_CL
tags: arXiv_CL Embedding
author: Nathaniel Swinger, Maria De-Arteaga, Neil Thomas Heffernan IV, Mark DM Leiserson, Adam Tauman Kalai
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents an algorithm for enumerating biases in word embeddings. The algorithm exposes a large number of offensive associations related to sensitive features such as race and gender on publicly available embeddings, including a supposedly "debiased" embedding. These embedded biases are concerning in light of the widespread use of word embeddings. The associations are identified by geometric patterns in word embeddings that run parallel between people's names and common lower-case words and phrases. The algorithm is highly unsupervised: it does not even require the sensitive groups (such as gender or race) to be pre-specified. This is desirable because it may not always be easy to identify all vulnerable groups a priori, and because it makes it easier to identify biases against intersectional groups, which depend on combinations of sensitive features. The inputs to our algorithm are a list of target tokens, e.g. names, and a word embedding, and the outputs are a number of Word Embedding Association Tests (WEATs) that capture various biases present in the data. We illustrate the utility of our approach on publicly available word embeddings and lists of names, and evaluate its output using crowdsourcing. We also show how removing names may not remove potential proxy bias.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.08769](http://arxiv.org/abs/1812.08769)

##### PDF
[http://arxiv.org/pdf/1812.08769](http://arxiv.org/pdf/1812.08769)

