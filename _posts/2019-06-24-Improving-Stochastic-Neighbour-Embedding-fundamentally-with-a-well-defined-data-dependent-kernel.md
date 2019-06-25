---
layout: post
title: "Improving Stochastic Neighbour Embedding fundamentally with a well-defined data-dependent kernel"
date: 2019-06-24 06:49:04
categories: arXiv_AI
tags: arXiv_AI Embedding Relation
author: Ye Zhu, Kai Ming Ting
mathjax: true
---

* content
{:toc}

##### Abstract
We identify a fundamental issue in the popular Stochastic Neighbour Embedding (SNE and t-SNE), i.e., the "learned" similarity of any two points in high-dimensional space is not defined and cannot be computed. It underlines two previously unexplored issues in the algorithm which have undermined the quality of its final visualisation output and its ability to process large datasets. The issues are:(a) the reference probability in high-dimensional space is set based on entropy which has undefined relation with local density; and (b) the use of data independent kernel which leads to the need to determine n bandwidths for a dataset of n points. This paper establishes a principle to set the reference probability via a data-dependent kernel which has a well-defined kernel characteristic that linked directly to local density. A solution based on a recent data-dependent kernel called Isolation Kernel addresses the fundamental issue as well as its two ensuing issues. As a result, it significantly improves the quality of the final visualisation output and removes one obstacle that prevents t-SNE from processing large datasets. The solution is extremely simple, i.e., simply replacing the existing data independent kernel with Isolation Kernel, leaving the rest of the t-SNE procedure unchanged.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.09744](http://arxiv.org/abs/1906.09744)

##### PDF
[http://arxiv.org/pdf/1906.09744](http://arxiv.org/pdf/1906.09744)

