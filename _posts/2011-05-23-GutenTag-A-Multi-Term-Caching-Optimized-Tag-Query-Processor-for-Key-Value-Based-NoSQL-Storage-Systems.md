---
layout: post
title: "GutenTag: A Multi-Term Caching Optimized Tag Query Processor for Key-Value Based NoSQL Storage Systems"
date: 2011-05-23 09:53:02
categories: arXiv_CV
tags: arXiv_CV Face
author: Christian von der Weth, Anwitaman Datta
mathjax: true
---

* content
{:toc}

##### Abstract
NoSQL systems are more and more deployed as back-end infrastructure for large-scale distributed online platforms like Google, Amazon or Facebook. Their applicability results from the fact that most services of online platforms access the stored data objects via their primary key. However, NoSQL systems do not efficiently support services referring more than one data object, e.g. the term-based search for data objects. To address this issue we propose our architecture based on an inverted index on top of a NoSQL system. For queries comprising more than one term, distributed indices yield a limited performance in large distributed systems. We propose two extensions to cope with this challenge. Firstly, we store index entries not only for single term but also for a selected set of term combinations depending on their popularity derived from a query history. Secondly, we additionally cache popular keys on gateway nodes, which are a common concept in real-world systems, acting as interface for services when accessing data objects in the back end. Our results show that we can significantly reduces the bandwidth consumption for processing queries, with an acceptable, marginal increase in the load of the gateway nodes.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1105.4452](https://arxiv.org/abs/1105.4452)

##### PDF
[https://arxiv.org/pdf/1105.4452](https://arxiv.org/pdf/1105.4452)

