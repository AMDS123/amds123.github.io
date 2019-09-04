---
layout: post
title: "Combining Spans into Entities: A Neural Two-Stage Approach for Recognizing Discontiguous Entities"
date: 2019-09-03 02:59:21
categories: arXiv_CL
tags: arXiv_CL
author: Bailin Wang, Wei Lu
mathjax: true
---

* content
{:toc}

##### Abstract
In medical documents, it is possible that an entity of interest not only contains a discontiguous sequence of words but also overlaps with another entity. Entities of such structures are intrinsically hard to recognize due to the large space of possible entity combinations. In this work, we propose a neural two-stage approach to recognize discontiguous and overlapping entities by decomposing this problem into two subtasks: 1) it first detects all the overlapping spans that either form entities on their own or present as segments of discontiguous entities, based on the representation of segmental hypergraph, 2) next it learns to combine these segments into discontiguous entities with a classifier, which filters out other incorrect combinations of segments. Two neural components are designed for these subtasks respectively and they are learned jointly using a shared encoder for text. Our model achieves the state-of-the-art performance in a standard dataset, even in the absence of external features that previous methods used.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.00930](http://arxiv.org/abs/1909.00930)

##### PDF
[http://arxiv.org/pdf/1909.00930](http://arxiv.org/pdf/1909.00930)

