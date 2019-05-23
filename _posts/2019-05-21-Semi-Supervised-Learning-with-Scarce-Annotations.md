---
layout: post
title: "Semi-Supervised Learning with Scarce Annotations"
date: 2019-05-21 19:41:42
categories: arXiv_CV
tags: arXiv_CV Transfer_Learning Classification
author: Sylvestre-Alvise Rebuffi, Sebastien Ehrhardt, Kai Han, Andrea Vedaldi, Andrew Zisserman
mathjax: true
---

* content
{:toc}

##### Abstract
While semi-supervised learning (SSL) algorithms provide an efficient way to make use of both labelled and unlabelled data, they generally struggle when the number of annotated samples is very small. In this work, we consider the problem of SSL multi-class classification with very few labelled instances. We introduce two key ideas. The first is a simple but effective one: we leverage the power of transfer learning among different tasks and self-supervision to initialize a good representation of the data without making use of any label. The second idea is a new algorithm for SSL that can exploit well such a pre-trained representation. 
 The algorithm works by alternating two phases, one fitting the labelled points and one fitting the unlabelled ones, with carefully-controlled information flow between them. The benefits are greatly reducing overfitting of the labelled data and avoiding issue with balancing labelled and unlabelled losses during training. We show empirically that this method can successfully train competitive models with as few as 10 labelled data points per class. More in general, we show that the idea of bootstrapping features using self-supervised learning always improves SSL on standard benchmarks. We show that our algorithm works increasingly well compared to other methods when refining from other tasks or datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.08845](http://arxiv.org/abs/1905.08845)

##### PDF
[http://arxiv.org/pdf/1905.08845](http://arxiv.org/pdf/1905.08845)

