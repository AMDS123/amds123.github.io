---
layout: post
title: "Fundamentals of effective cloud management for the new NASA Astrophysics Data System"
date: 2019-01-16 19:00:01
categories: arXiv_CV
tags: arXiv_CV
author: Sergi Blanco-Cuaresma, Alberto Accomazzi, Michael J. Kurtz, Edwin Henneken, Carolyn S. Grant, Donna M. Thompson, Roman Chyla, Stephen McDonald, Golnaz Shapurian, Timothy W. Hostetler, Matthew R. Templeton, Kelly E. Lockhart, Kris Bukovi, Nathan Rapport
mathjax: true
---

* content
{:toc}

##### Abstract
The new NASA Astrophysics Data System (ADS) is designed with a serviceoriented architecture (SOA) that consists of multiple customized Apache Solr search engine instances plus a collection of microservices, containerized using Docker, and deployed in Amazon Web Services (AWS). For complex systems, like the ADS, this loosely coupled architecture can lead to a more scalable, reliable and resilient system if some fundamental questions are addressed. After having experimented with different AWS environments and deployment methods, we decided in December 2017 to go with Kubernetes as our container orchestration. Defining the best strategy to properly setup Kubernetes has shown to be challenging: automatic scaling services and load balancing traffic can lead to errors whose origin is difficult to identify, monitoring and logging the activity that happens across multiple layers for a single request needs to be carefully addressed, and the best workflow for a Continuous Integration and Delivery (CI/CD) system is not self-evident. We present here how we tackle these challenges and our plans for the future.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1901.05463](https://arxiv.org/abs/1901.05463)

##### PDF
[https://arxiv.org/pdf/1901.05463](https://arxiv.org/pdf/1901.05463)

