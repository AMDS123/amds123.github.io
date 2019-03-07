---
layout: post
title: "KBQA: Learning Question Answering over QA Corpora and Knowledge Bases"
date: 2019-03-06 14:38:28
categories: arXiv_CL
tags: arXiv_CL Knowledge QA
author: Wanyun Cui, Yanghua Xiao, Haixun Wang, Yangqiu Song, Seung-won Hwang, Wei Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Question answering (QA) has become a popular way for humans to access billion-scale knowledge bases. Unlike web search, QA over a knowledge base gives out accurate and concise results, provided that natural language questions can be understood and mapped precisely to structured queries over the knowledge base. The challenge, however, is that a human can ask one question in many different ways. Previous approaches have natural limits due to their representations: rule based approaches only understand a small set of "canned" questions, while keyword based or synonym based approaches cannot fully understand the questions. In this paper, we design a new kind of question representation: templates, over a billion scale knowledge base and a million scale QA corpora. For example, for questions about a city's population, we learn templates such as What's the population of $city?, How many people are there in $city?. We learned 27 million templates for 2782 intents. Based on these templates, our QA system KBQA effectively supports binary factoid questions, as well as complex questions which are composed of a series of binary factoid questions. Furthermore, we expand predicates in RDF knowledge base, which boosts the coverage of knowledge base by 57 times. Our QA system beats all other state-of-art works on both effectiveness and efficiency over QALD benchmarks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.02419](http://arxiv.org/abs/1903.02419)

##### PDF
[http://arxiv.org/pdf/1903.02419](http://arxiv.org/pdf/1903.02419)

