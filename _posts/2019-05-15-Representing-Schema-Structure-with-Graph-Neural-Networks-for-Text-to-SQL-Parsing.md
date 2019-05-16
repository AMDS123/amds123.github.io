---
layout: post
title: "Representing Schema Structure with Graph Neural Networks for Text-to-SQL Parsing"
date: 2019-05-15 15:22:01
categories: arXiv_CL
tags: arXiv_CL
author: Ben Bogin, Matt Gardner, Jonathan Berant
mathjax: true
---

* content
{:toc}

##### Abstract
Research on parsing language to SQL has largely ignored the structure of the database (DB) schema, either because the DB was very simple, or because it was observed at both training and test time. In \spider{}, a recently-released text-to-SQL dataset, new and complex DBs are given at test time, and so the structure of the DB schema can inform the predicted SQL query. In this paper, we present an encoder-decoder semantic parser, where the structure of the DB schema is encoded with a graph neural network, and this representation is later used at both encoding and decoding time. Evaluation shows that encoding the schema structure improves our parser accuracy from 33.8% to 39.4%, dramatically above the current state of the art, which is at 19.7%.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.06241](http://arxiv.org/abs/1905.06241)

##### PDF
[http://arxiv.org/pdf/1905.06241](http://arxiv.org/pdf/1905.06241)

