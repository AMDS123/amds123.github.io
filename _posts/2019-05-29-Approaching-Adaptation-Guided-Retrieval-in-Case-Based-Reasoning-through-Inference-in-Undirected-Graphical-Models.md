---
layout: post
title: "Approaching Adaptation Guided Retrieval in Case-Based Reasoning through Inference in Undirected Graphical Models"
date: 2019-05-29 14:00:26
categories: arXiv_AI
tags: arXiv_AI Knowledge Inference
author: Luigi Portinale
mathjax: true
---

* content
{:toc}

##### Abstract
In Case-Based Reasoning, when the similarity assumption does not hold, the retrieval of a set of cases structurally similar to the query does not guarantee to get a reusable or revisable solution. Knowledge about the adaptability of solutions has to be exploited, in order to define a method for adaptation-guided retrieval. We propose a novel approach to address this problem, where knowledge about the adaptability of the solutions is captured inside a metric Markov Random Field (MRF). Nodes of the MRF represent cases and edges connect nodes whose solutions are close in the solution space. States of the nodes represent different adaptation levels with respect to the potential query. Metric-based potentials enforce connected nodes to share the same state, since cases having similar solutions should have the same adaptability level with respect to the query. The main goal is to enlarge the set of potentially adaptable cases that are retrieved without significantly sacrificing the precision and accuracy of retrieval. We will report on some experiments concerning a retrieval architecture where a simple kNN retrieval (on the problem description) is followed by a further retrieval step based on MRF inference.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.12464](http://arxiv.org/abs/1905.12464)

##### PDF
[http://arxiv.org/pdf/1905.12464](http://arxiv.org/pdf/1905.12464)

