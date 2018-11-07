---
layout: post
title: "DIAG-NRE: A Deep Pattern Diagnosis Framework for Distant Supervision Neural Relation Extraction"
date: 2018-11-06 05:08:59
categories: arXiv_CL
tags: arXiv_CL Review Relation_Extraction Reinforcement_Learning Quantitative Relation
author: Shun Zheng, Peilin Yu, Lu Chen, Ling Huang, Wei Xu
mathjax: true
---

* content
{:toc}

##### Abstract
Modern neural network models have achieved the state-of-the-art performance on relation extraction (RE) tasks. Although distant supervision (DS) can automatically generate training labels for RE, the effectiveness of DS highly depends on datasets and relation types, and sometimes it may introduce large labeling noises. In this paper, we propose a deep pattern diagnosis framework, DIAG-NRE, that aims to diagnose and improve neural relation extraction (NRE) models trained on DS-generated data. DIAG-NRE includes three stages: (1) The deep pattern extraction stage employs reinforcement learning to extract regular-expression-style patterns from NRE models. (2) The pattern refinement stage builds a pattern hierarchy to find the most representative patterns and lets human reviewers evaluate them quantitatively by annotating a certain number of pattern-matched examples. In this way, we minimize both the number of labels to annotate and the difficulty of writing heuristic patterns. (3) The weak label fusion stage fuses multiple weak label sources, including DS and refined patterns, to produce noise-reduced labels that can train a better NRE model. To demonstrate the broad applicability of DIAG-NRE, we use it to diagnose 14 relation types of two public datasets with one simple hyper-parameter configuration. We observe different noise behaviors and obtain significant F1 improvements on all relation types suffering from large labeling noises.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.02166](http://arxiv.org/abs/1811.02166)

##### PDF
[http://arxiv.org/pdf/1811.02166](http://arxiv.org/pdf/1811.02166)

