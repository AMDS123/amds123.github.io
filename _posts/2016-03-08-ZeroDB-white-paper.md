---
layout: post
title: "ZeroDB white paper"
date: 2016-03-08 18:01:18
categories: arXiv_CV
tags: arXiv_CV
author: Michael Egorov, MacLane Wilkison
mathjax: true
---

* content
{:toc}

##### Abstract
ZeroDB is an end-to-end encrypted database that enables clients to operate on (search, sort, query, and share) encrypted data without exposing encryption keys or cleartext data to the database server. The familiar client-server architecture is unchanged, but query logic and encryption keys are pushed client-side. Since the server has no insight into the nature of the data, the risk of data being exposed via a server-side data breach is eliminated. Even if the server is successfully infiltrated, adversaries would not have access to the cleartext data and cannot derive anything useful out of disk or RAM snapshots. ZeroDB provides end-to-end encryption while maintaining much of the functionality expected of a modern database, such as full-text search, sort, and range queries. Additionally, ZeroDB uses proxy re-encryption and/or delta key technology to enable secure, granular sharing of encrypted data without exposing keys to the server and without sharing the same encryption key between users of the database.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1602.07168](https://arxiv.org/abs/1602.07168)

##### PDF
[https://arxiv.org/pdf/1602.07168](https://arxiv.org/pdf/1602.07168)

