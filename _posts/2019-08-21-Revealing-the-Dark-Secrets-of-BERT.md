---
layout: post
title: "Revealing the Dark Secrets of BERT"
date: 2019-08-21 04:27:38
categories: arXiv_CL
tags: arXiv_CL Attention Quantitative
author: Olga Kovaleva, Alexey Romanov, Anna Rogers, Anna Rumshisky
mathjax: true
---

* content
{:toc}

##### Abstract
BERT-based architectures currently give state-of-the-art performance on many NLP tasks, but little is known about the exact mechanisms that contribute to its success. In the current work, we focus on the interpretation of self-attention, which is one of the fundamental underlying components of BERT. Using a subset of GLUE tasks and a set of handcrafted features-of-interest, we propose the methodology and carry out a qualitative and quantitative analysis of the information encoded by the individual BERT's heads. Our findings suggest that there is a limited set of attention patterns that are repeated across different heads, indicating the overall model overparametrization. While different heads consistently use the same attention patterns, they have varying impact on performance across different tasks. We show that manually disabling attention in certain heads leads to a performance improvement over the regular fine-tuned BERT models.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.08593](http://arxiv.org/abs/1908.08593)

##### PDF
[http://arxiv.org/pdf/1908.08593](http://arxiv.org/pdf/1908.08593)

