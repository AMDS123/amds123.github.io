---
layout: post
title: "SemBleu: A Robust Metric for AMR Parsing Evaluation"
date: 2019-05-26 04:49:29
categories: arXiv_CL
tags: arXiv_CL
author: Linfeng Song, Daniel Gildea
mathjax: true
---

* content
{:toc}

##### Abstract
Evaluating AMR parsing accuracy involves comparing pairs of AMR graphs. The only existing evaluation metric, Smatch (Cai and Knight, 2013), searches for one-to-one mappings between the nodes of two AMRs with a greedy hill-climbing algorithm, which leads to search errors. We propose SemBleu, a robust metric that extends BLEU (Papineni et al., 2002) to AMRs. It does not suffer from search errors and considers non-local correspondences in addition to local ones. SemBleu is fully content-driven and punishes situations where a system output does not preserve most information from the input. Preliminary experiments on both sentence and corpus levels show that SemBleu has slightly higher consistency with human judgments than Smatch. Our code and data at <a href="http://github.">this http URL</a> com/freesunshine0316/sembleu.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.10726](http://arxiv.org/abs/1905.10726)

##### PDF
[http://arxiv.org/pdf/1905.10726](http://arxiv.org/pdf/1905.10726)

