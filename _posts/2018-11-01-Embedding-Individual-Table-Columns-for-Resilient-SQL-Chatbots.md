---
layout: post
title: "Embedding Individual Table Columns for Resilient SQL Chatbots"
date: 2018-11-01 21:03:41
categories: arXiv_CL
tags: arXiv_CL Knowledge QA Embedding Relation
author: Bojan Petrovski, Ignacio Aguado, Andreea Hossmann, Michael Baeriswyl, Claudiu Musat
mathjax: true
---

* content
{:toc}

##### Abstract
Most of the world's data is stored in relational databases. Accessing these requires specialized knowledge of the Structured Query Language (SQL), putting them out of the reach of many people. A recent research thread in Natural Language Processing (NLP) aims to alleviate this problem by automatically translating natural language questions into SQL queries. While the proposed solutions are a great start, they lack robustness and do not easily generalize: the methods require high quality descriptions of the database table columns, and the most widely used training dataset, WikiSQL, is heavily biased towards using those descriptions as part of the questions. 
 In this work, we propose solutions to both problems: we entirely eliminate the need for column descriptions, by relying solely on their contents, and we augment the WikiSQL dataset by paraphrasing column names to reduce bias. We show that the accuracy of existing methods drops when trained on our augmented, column-agnostic dataset, and that our own method reaches state of the art accuracy, while relying on column contents only.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.00633](http://arxiv.org/abs/1811.00633)

##### PDF
[http://arxiv.org/pdf/1811.00633](http://arxiv.org/pdf/1811.00633)

