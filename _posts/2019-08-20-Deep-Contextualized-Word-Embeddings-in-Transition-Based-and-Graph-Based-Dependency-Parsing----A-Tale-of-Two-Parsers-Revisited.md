---
layout: post
title: "Deep Contextualized Word Embeddings in Transition-Based and Graph-Based Dependency Parsing -- A Tale of Two Parsers Revisited"
date: 2019-08-20 14:36:57
categories: arXiv_CL
tags: arXiv_CL Embedding Optimization
author: Artur Kulmizev, Miryam de Lhoneux, Johannes Gontrum, Elena Fano, Joakim Nivre
mathjax: true
---

* content
{:toc}

##### Abstract
Transition-based and graph-based dependency parsers have previously been shown to have complementary strengths and weaknesses: transition-based parsers exploit rich structural features but suffer from error propagation, while graph-based parsers benefit from global optimization but have restricted feature scope. In this paper, we show that, even though some details of the picture have changed after the switch to neural networks and continuous representations, the basic trade-off between rich features and global optimization remains essentially the same. Moreover, we show that deep contextualized word embeddings, which allow parsers to pack information about global sentence structure into local feature representations, benefit transition-based parsers more than graph-based parsers, making the two approaches virtually equivalent in terms of both accuracy and error profile. We argue that the reason is that these representations help prevent search errors and thereby allow transition-based parsers to better exploit their inherent strength of making accurate local decisions. We support this explanation by an error analysis of parsing experiments on 13 languages.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.07397](http://arxiv.org/abs/1908.07397)

##### PDF
[http://arxiv.org/pdf/1908.07397](http://arxiv.org/pdf/1908.07397)

