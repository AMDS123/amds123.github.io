---
layout: post
title: "Learning Fair Naive Bayes Classifiers by Discovering and Eliminating Discrimination Patterns"
date: 2019-06-10 08:48:19
categories: arXiv_AI
tags: arXiv_AI Classification
author: YooJung Choi, Golnoosh Farnadi, Behrouz Babaki, Guy Van den Broeck
mathjax: true
---

* content
{:toc}

##### Abstract
As machine learning is increasingly used to make real-world decisions, recent research efforts aim to define and ensure fairness in algorithmic decision making. Existing methods often assume a fixed set of observable features to define individuals, but lack a discussion of certain features not being observed at test time. In this paper, we study fairness of naive Bayes classifiers, which allow partial observations. In particular, we introduce the notion of a discrimination pattern, which refers to an individual receiving different classifications depending on whether some sensitive attributes were observed. Then a model is considered fair if it has no such pattern. We propose an algorithm to discover and mine for discrimination patterns in a naive Bayes classifier, and show how to learn maximum-likelihood parameters subject to these fairness constraints. Our approach iteratively discovers and eliminates discrimination patterns until a fair model is learned. An empirical evaluation on three real-world datasets demonstrates that we can remove exponentially many discrimination patterns by only adding a small fraction of them as constraints.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.03843](http://arxiv.org/abs/1906.03843)

##### PDF
[http://arxiv.org/pdf/1906.03843](http://arxiv.org/pdf/1906.03843)

