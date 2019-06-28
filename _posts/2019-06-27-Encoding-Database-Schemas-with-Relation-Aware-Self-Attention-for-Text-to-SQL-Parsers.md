---
layout: post
title: "Encoding Database Schemas with Relation-Aware Self-Attention for Text-to-SQL Parsers"
date: 2019-06-27 16:52:29
categories: arXiv_AI
tags: arXiv_AI Attention Relation
author: Richard Shin
mathjax: true
---

* content
{:toc}

##### Abstract
When translating natural language questions into SQL queries to answer questions from a database, we would like our methods to generalize to domains and database schemas outside of the training set. To handle complex questions and database schemas with a neural encoder-decoder paradigm, it is critical to properly encode the schema as part of the input with the question. In this paper, we use relation-aware self-attention within the encoder so that it can reason about how the tables and columns in the provided schema relate to each other and use this information in interpreting the question. We achieve significant gains on the recently-released Spider dataset with 42.94% exact match accuracy, compared to the 18.96% reported in published work.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.11790](http://arxiv.org/abs/1906.11790)

##### PDF
[http://arxiv.org/pdf/1906.11790](http://arxiv.org/pdf/1906.11790)

