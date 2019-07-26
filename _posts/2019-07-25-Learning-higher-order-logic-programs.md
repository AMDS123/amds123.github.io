---
layout: post
title: "Learning higher-order logic programs"
date: 2019-07-25 10:36:01
categories: arXiv_AI
tags: arXiv_AI Knowledge
author: Andrew Cropper, Rolf Morel, Stephen H. Muggleton
mathjax: true
---

* content
{:toc}

##### Abstract
A key feature of inductive logic programming (ILP) is its ability to learn first-order programs, which are intrinsically more expressive than propositional programs. In this paper, we introduce techniques to learn higher-order programs. Specifically, we extend meta-interpretive learning (MIL) to support learning higher-order programs by allowing for \emph{higher-order definitions} to be used as background knowledge. Our theoretical results show that learning higher-order programs, rather than first-order programs, can reduce the textual complexity required to express programs which in turn reduces the size of the hypothesis space and sample complexity. We implement our idea in two new MIL systems: the Prolog system \namea{} and the ASP system \nameb{}. Both systems support learning higher-order programs and higher-order predicate invention, such as inventing functions for \tw{map/3} and conditions for \tw{filter/3}. We conduct experiments on four domains (robot strategies, chess playing, list transformations, and string decryption) that compare learning first-order and higher-order programs. Our experimental results support our theoretical claims and show that, compared to learning first-order programs, learning higher-order programs can significantly improve predictive accuracies and reduce learning times.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.10953](http://arxiv.org/abs/1907.10953)

##### PDF
[http://arxiv.org/pdf/1907.10953](http://arxiv.org/pdf/1907.10953)

