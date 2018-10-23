---
layout: post
title: "Constituent Parsing as Sequence Labeling"
date: 2018-10-21 17:59:52
categories: arXiv_CL
tags: arXiv_CL
author: Carlos G&#xf3;mez-Rodr&#xed;guez, David Vilares
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a method to reduce constituent parsing to sequence labeling. For each word w_t, it generates a label that encodes: (1) the number of ancestors in the tree that the words w_t and w_{t+1} have in common, and (2) the nonterminal symbol at the lowest common ancestor. We first prove that the proposed encoding function is injective for any tree without unary branches. In practice, the approach is made extensible to all constituency trees by collapsing unary branches. We then use the PTB and CTB treebanks as testbeds and propose a set of fast baselines. We achieve 90% F-score on the PTB test set, outperforming the Vinyals et al. (2015) sequence-to-sequence parser. In addition, sacrificing some accuracy, our approach achieves the fastest constituent parsing speeds reported to date on PTB by a wide margin.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.08994](http://arxiv.org/abs/1810.08994)

##### PDF
[http://arxiv.org/pdf/1810.08994](http://arxiv.org/pdf/1810.08994)

