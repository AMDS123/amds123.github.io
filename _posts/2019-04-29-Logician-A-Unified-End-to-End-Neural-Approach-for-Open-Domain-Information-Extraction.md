---
layout: post
title: "Logician: A Unified End-to-End Neural Approach for Open-Domain Information Extraction"
date: 2019-04-29 09:37:31
categories: arXiv_AI
tags: arXiv_AI Knowledge Relation_Extraction Attention Optimization Relation
author: Mingming Sun, Xu Li, Xin Wang, Miao Fan, Yue Feng, Ping Li
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we consider the problem of open information extraction (OIE) for extracting entity and relation level intermediate structures from sentences in open-domain. We focus on four types of valuable intermediate structures (Relation, Attribute, Description, and Concept), and propose a unified knowledge expression form, SAOKE, to express them. We publicly release a data set which contains more than forty thousand sentences and the corresponding facts in the SAOKE format labeled by crowd-sourcing. To our knowledge, this is the largest publicly available human labeled data set for open information extraction tasks. Using this labeled SAOKE data set, we train an end-to-end neural model using the sequenceto-sequence paradigm, called Logician, to transform sentences into facts. For each sentence, different to existing algorithms which generally focus on extracting each single fact without concerning other possible facts, Logician performs a global optimization over all possible involved facts, in which facts not only compete with each other to attract the attention of words, but also cooperate to share words. An experimental study on various types of open domain relation extraction tasks reveals the consistent superiority of Logician to other states-of-the-art algorithms. The experiments verify the reasonableness of SAOKE format, the valuableness of SAOKE data set, the effectiveness of the proposed Logician model, and the feasibility of the methodology to apply end-to-end learning paradigm on supervised data sets for the challenging tasks of open information extraction.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.12535](http://arxiv.org/abs/1904.12535)

##### PDF
[http://arxiv.org/pdf/1904.12535](http://arxiv.org/pdf/1904.12535)

