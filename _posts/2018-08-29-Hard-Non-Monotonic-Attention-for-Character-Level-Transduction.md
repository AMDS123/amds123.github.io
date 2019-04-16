---
layout: post
title: "Hard Non-Monotonic Attention for Character-Level Transduction"
date: 2018-08-29 20:00:20
categories: arXiv_CV
tags: arXiv_CV Image_Caption Attention Caption
author: Shijie Wu, Pamela Shapiro, Ryan Cotterell
mathjax: true
---

* content
{:toc}

##### Abstract
Character-level string-to-string transduction is an important component of various NLP tasks. The goal is to map an input string to an output string, where the strings may be of different lengths and have characters taken from different alphabets. Recent approaches have used sequence-to-sequence models with an attention mechanism to learn which parts of the input string the model should focus on during the generation of the output string. Both soft attention and hard monotonic attention have been used, but hard non-monotonic attention has only been used in other sequence modeling tasks such as image captioning and has required a stochastic approximation to compute the gradient. In this work, we introduce an exact, polynomial-time algorithm for marginalizing over the exponential number of non-monotonic alignments between two strings, showing that hard attention models can be viewed as neural reparameterizations of the classical IBM Model 1. We compare soft and hard non-monotonic attention experimentally and find that the exact algorithm significantly improves performance over the stochastic approximation and outperforms soft attention.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1808.10024](https://arxiv.org/abs/1808.10024)

##### PDF
[https://arxiv.org/pdf/1808.10024](https://arxiv.org/pdf/1808.10024)

