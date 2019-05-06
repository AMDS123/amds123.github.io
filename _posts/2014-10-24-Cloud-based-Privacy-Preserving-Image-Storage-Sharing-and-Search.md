---
layout: post
title: "Cloud-based Privacy Preserving Image Storage, Sharing and Search"
date: 2014-10-24 06:44:59
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Lan Zhang, Taeho Jung, Puchun Feng, Xiang-Yang Li, Yunhao Liu
mathjax: true
---

* content
{:toc}

##### Abstract
High-resolution cameras produce huge volume of high quality images everyday. It is extremely challenging to store, share and especially search those huge images, for which increasing number of cloud services are presented to support such functionalities. However, images tend to contain rich sensitive information (\eg, people, location and event), and people's privacy concerns hinder their readily participation into the services provided by untrusted third parties. In this work, we introduce PIC: a Privacy-preserving large-scale Image search system on Cloud. Our system enables efficient yet secure content-based image search with fine-grained access control, and it also provides privacy-preserving image storage and sharing among users. Users can specify who can/cannot search on their images when using the system, and they can search on others' images if they satisfy the condition specified by the image owners. Majority of the computationally intensive jobs are outsourced to the cloud side, and users only need to submit the query and receive the result throughout the entire image search. Specially, to deal with massive images, we design our system suitable for distributed and parallel computation and introduce several optimizations to further expedite the search process. We implement a prototype of PIC including both cloud side and client side. The cloud side is a cluster of computers with distributed file system (Hadoop HDFS) and MapReduce architecture (Hadoop MapReduce). The client side is built for both Windows OS laptops and Android phones. We evaluate the prototype system with large sets of real-life photos. Our security analysis and evaluation results show that PIC successfully protect the image privacy at a low cost of computation and communication.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1410.6593](https://arxiv.org/abs/1410.6593)

##### PDF
[https://arxiv.org/pdf/1410.6593](https://arxiv.org/pdf/1410.6593)

