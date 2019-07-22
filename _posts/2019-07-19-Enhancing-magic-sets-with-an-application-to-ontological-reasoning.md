---
layout: post
title: "Enhancing magic sets with an application to ontological reasoning"
date: 2019-07-19 09:31:26
categories: arXiv_AI
tags: arXiv_AI
author: Mario Alviano, Nicola Leone, Pierfrancesco Veltri, Jessica Zangari
mathjax: true
---

* content
{:toc}

##### Abstract
Magic sets are a Datalog to Datalog rewriting technique to optimize query answering. The rewritten program focuses on a portion of the stable model(s) of the input program which is sufficient to answer the given query. However, the rewriting may introduce new recursive definitions, which can involve even negation and aggregations, and may slow down program evaluation. This paper enhances the magic set technique by preventing the creation of (new) recursive definitions in the rewritten program. It turns out that the new version of magic sets is closed for Datalog programs with stratified negation and aggregations, which is very convenient to obtain efficient computation of the stable model of the rewritten program. Moreover, the rewritten program is further optimized by the elimination of subsumed rules and by the efficient handling of the cases where binding propagation is lost. The research was stimulated by a challenge on the exploitation of Datalog/\textsc{dlv} for efficient reasoning on large ontologies. All proposed techniques have been hence implemented in the \textsc{dlv} system, and tested for ontological reasoning, confirming their effectiveness. 
 Under consideration for publication in Theory and Practice of Logic Programming.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.08424](http://arxiv.org/abs/1907.08424)

##### PDF
[http://arxiv.org/pdf/1907.08424](http://arxiv.org/pdf/1907.08424)

