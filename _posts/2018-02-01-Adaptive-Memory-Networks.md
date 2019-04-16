---
layout: post
title: "Adaptive Memory Networks"
date: 2018-02-01 22:33:56
categories: arXiv_CV
tags: arXiv_CV QA Inference Memory_Networks
author: Daniel Li, Asim Kadav
mathjax: true
---

* content
{:toc}

##### Abstract
We present Adaptive Memory Networks (AMN) that processes input-question pairs to dynamically construct a network architecture optimized for lower inference times for Question Answering (QA) tasks. AMN processes the input story to extract entities and stores them in memory banks. Starting from a single bank, as the number of input entities increases, AMN learns to create new banks as the entropy in a single bank becomes too high. Hence, after processing an input-question(s) pair, the resulting network represents a hierarchical structure where entities are stored in different banks, distanced by question relevance. At inference, one or few banks are used, creating a tradeoff between accuracy and performance. AMN is enabled by dynamic networks that allow input dependent network creation and efficiency in dynamic mini-batching as well as our novel bank controller that allows learning discrete decision making with high accuracy. In our results, we demonstrate that AMN learns to create variable depth networks depending on task complexity and reduces inference times for QA tasks.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1802.00510](https://arxiv.org/abs/1802.00510)

##### PDF
[https://arxiv.org/pdf/1802.00510](https://arxiv.org/pdf/1802.00510)

