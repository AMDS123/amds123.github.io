---
layout: post
title: "ODYS: A Massively-Parallel Search Engine Using a DB-IR Tightly-Integrated Parallel DBMS"
date: 2012-08-21 14:01:36
categories: arXiv_CV
tags: arXiv_CV Face
author: Kyu-Young Whang, Tae-Seob Yun, Yeon-Mi Yeo, Il-Yeol Song, Hyuk-Yoon Kwon, In-Joong Kim
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, parallel search engines have been implemented based on scalable distributed file systems such as Google File System. However, we claim that building a massively-parallel search engine using a parallel DBMS can be an attractive alternative since it supports a higher-level (i.e., SQL-level) interface than that of a distributed file system for easy and less error-prone application development while providing scalability. In this paper, we propose a new approach of building a massively-parallel search engine using a DB-IR tightly-integrated parallel DBMS and demonstrate its commercial-level scalability and performance. In addition, we present a hybrid (i.e., analytic and experimental) performance model for the parallel search engine. We have built a five-node parallel search engine according to the proposed architecture using a DB-IR tightly-integrated DBMS. Through extensive experiments, we show the correctness of the model by comparing the projected output with the experimental results of the five-node engine. Our model demonstrates that ODYS is capable of handling 1 billion queries per day (81 queries/sec) for 30 billion web pages by using only 43,472 nodes with an average query response time of 211 ms, which is equivalent to or better than those of commercial search engines. We also show that, by using twice as many (86,944) nodes, ODYS can provide an average query response time of 162 ms, which is significantly lower than those of commercial search engines.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1208.4270](https://arxiv.org/abs/1208.4270)

##### PDF
[https://arxiv.org/pdf/1208.4270](https://arxiv.org/pdf/1208.4270)

