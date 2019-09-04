---
layout: post
title: "A Sketch-Based System for Semantic Parsing"
date: 2019-09-02 07:16:57
categories: arXiv_CL
tags: arXiv_CL Optimization Classification Relation
author: Zechang Li, Yuxuan Lai, Yuxi Xie, Yansong Feng, Dongyan Zhao
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents our semantic parsing system for the evaluation task of open domain semantic parsing in NLPCC 2019. Many previous works formulate semantic parsing as a sequence-to-sequence(seq2seq) problem. Instead, we treat the task as a sketch-based problem in a coarse-to-fine(coarse2fine) fashion. The sketch is a high-level structure of the logical form exclusive of low-level details such as entities and predicates. In this way, we are able to optimize each part individually. Specifically, we decompose the process into three stages: the sketch classification determines the high-level structure while the entity labeling and the matching network fill in missing details. Moreover, we adopt the seq2seq method to evaluate logical form candidates from an overall perspective. The co-occurrence relationship between predicates and entities contribute to the reranking as well. Our submitted system achieves the exactly matching accuracy of 82.53% on full test set and 47.83% on hard test subset, which is the 3rd place in NLPCC 2019 Shared Task 2. After optimizations for parameters, network structure and sampling, the accuracy reaches 84.47% on full test set and 63.08% on hard test subset.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.00574](http://arxiv.org/abs/1909.00574)

##### PDF
[http://arxiv.org/pdf/1909.00574](http://arxiv.org/pdf/1909.00574)

