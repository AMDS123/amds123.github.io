---
layout: post
title: "What Does BERT Look At? An Analysis of BERT's Attention"
date: 2019-06-11 01:31:41
categories: arXiv_CL
tags: arXiv_CL Attention Language_Model
author: Kevin Clark, Urvashi Khandelwal, Omer Levy, Christopher D. Manning
mathjax: true
---

* content
{:toc}

##### Abstract
Large pre-trained neural networks such as BERT have had great recent success in NLP, motivating a growing body of research investigating what aspects of language they are able to learn from unlabeled data. Most recent analysis has focused on model outputs (e.g., language model surprisal) or internal vector representations (e.g., probing classifiers). Complementary to these works, we propose methods for analyzing the attention mechanisms of pre-trained models and apply them to BERT. BERT's attention heads exhibit patterns such as attending to delimiter tokens, specific positional offsets, or broadly attending over the whole sentence, with heads in the same layer often exhibiting similar behaviors. We further show that certain attention heads correspond well to linguistic notions of syntax and coreference. For example, we find heads that attend to the direct objects of verbs, determiners of nouns, objects of prepositions, and coreferent mentions with remarkably high accuracy. Lastly, we propose an attention-based probing classifier and use it to further demonstrate that substantial syntactic information is captured in BERT's attention.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.04341](http://arxiv.org/abs/1906.04341)

##### PDF
[http://arxiv.org/pdf/1906.04341](http://arxiv.org/pdf/1906.04341)

