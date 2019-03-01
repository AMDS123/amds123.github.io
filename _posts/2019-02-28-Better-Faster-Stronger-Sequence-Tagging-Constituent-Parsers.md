---
layout: post
title: "Better, Faster, Stronger Sequence Tagging Constituent Parsers"
date: 2019-02-28 10:06:20
categories: arXiv_CL
tags: arXiv_CL
author: David Vilares, Mostafa Abdou, Anders S&#xf8;gaard
mathjax: true
---

* content
{:toc}

##### Abstract
Sequence tagging models for constituent parsing are faster, but less accurate than other types of parsers. In this work, we address the following weaknesses of such constituent parsers: (a) high error rates around closing brackets of long constituents, (b) large label sets, leading to sparsity, and (c) error propagation arising from greedy decoding. To effectively close brackets, we train a model that learns to switch between tagging schemes. To reduce sparsity, we decompose the label set and use multi-task learning to jointly learn to predict sublabels. Finally, we mitigate issues from greedy decoding through auxiliary losses and sentence-level fine-tuning with policy gradient. Combining these techniques, we clearly surpass the performance of sequence tagging constituent parsers on the English and Chinese Penn Treebanks, and reduce their parsing time even further. On the SPMRL datasets, we observe even greater improvements across the board, including a new state of the art on Basque, Hebrew, Polish and Swedish.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.10985](http://arxiv.org/abs/1902.10985)

##### PDF
[http://arxiv.org/pdf/1902.10985](http://arxiv.org/pdf/1902.10985)

