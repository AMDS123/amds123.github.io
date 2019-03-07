---
layout: post
title: "FIESTA: Fast Incremental Euclidean Distance Fields for Online Motion Planning of Aerial Robots"
date: 2019-03-06 02:31:47
categories: arXiv_RO
tags: arXiv_RO
author: Luxin Han, Fei Gao, Boyu Zhou, Shaojie Shen
mathjax: true
---

* content
{:toc}

##### Abstract
Euclidean Signed Distance Field (ESDF) is useful for online motion planning of aerial robots since it can easily query the distance and gradient information against obstacles. Fast incrementally built ESDF map is the bottleneck for conducting real-time motion planning. In this paper, we investigate this problem and propose a mapping system called FIESTA to build global ESDF map incrementally. By introducing two independent updating queues for inserting and deleting obstacles separately, and using Indexing Data Structures and Doubly Linked Lists for map maintenance, our algorithm updates as few as possible nodes using a BFS framework. Our ESDF map has high computational performance and produces near-optimal results. We show our method outperforms other up-to-date methods in term of performance and accuracy by both theory and experiments. We integrate FIESTA into a completed quadrotor system and validate it by both simulation and onboard experiments. We release our method as open-source software for the community.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.02144](http://arxiv.org/abs/1903.02144)

##### PDF
[http://arxiv.org/pdf/1903.02144](http://arxiv.org/pdf/1903.02144)

