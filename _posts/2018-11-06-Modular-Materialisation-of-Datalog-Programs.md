---
layout: post
title: "Modular Materialisation of Datalog Programs"
date: 2018-11-06 11:51:10
categories: arXiv_AI
tags: arXiv_AI Relation
author: Pan Hu, Boris Motik, Ian Horrocks
mathjax: true
---

* content
{:toc}

##### Abstract
The seminaïve algorithm can materialise all consequences of arbitrary datalog rules, and it also forms the basis for incremental algorithms that update a materialisation as the input facts change. Certain (combinations of) rules, however, can be handled much more efficiently using custom algorithms. To integrate such algorithms into a general reasoning approach that can handle arbitrary rules, we propose a modular framework for materialisation computation and its maintenance. We split a datalog program into modules that can be handled using specialised algorithms, and handle the remaining rules using the seminaïve algorithm. We also present two algorithms for computing the transitive and the symmetric-transitive closure of a relation that can be used within our framework. Finally, we show empirically that our framework can handle arbitrary datalog programs while outperforming existing approaches, often by orders of magnitude.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1811.02304](https://arxiv.org/abs/1811.02304)

##### PDF
[https://arxiv.org/pdf/1811.02304](https://arxiv.org/pdf/1811.02304)

