---
layout: post
title: "Enabling Lock-Free Concurrent Fine-Grain Access to Massive Distributed Data: Application to Supernovae Detection"
date: 2008-10-13 13:07:18
categories: arXiv_CV
tags: arXiv_CV Detection
author: Bogdan Nicolae (IRISA), Gabriel Antoniu (IRISA), Luc Bougé (IRISA)
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the problem of efficiently managing massive data in a large-scale distributed environment. We consider data strings of size in the order of Terabytes, shared and accessed by concurrent clients. On each individual access, a segment of a string, of the order of Megabytes, is read or modified. Our goal is to provide the clients with efficient fine-grain access the data string as concurrently as possible, without locking the string itself. This issue is crucial in the context of applications in the field of astronomy, databases, data mining and multimedia. We illustrate these requiremens with the case of an application for searching supernovae. Our solution relies on distributed, RAM-based data storage, while leveraging a DHT-based, parallel metadata management scheme. The proposed architecture and algorithms have been validated through a software prototype and evaluated in a cluster environment.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/0810.2226](https://arxiv.org/abs/0810.2226)

##### PDF
[https://arxiv.org/pdf/0810.2226](https://arxiv.org/pdf/0810.2226)

