---
layout: post
title: "Well-Founded Operators for Normal Hybrid MKNF Knowledge Bases"
date: 2017-07-12 22:50:14
categories: arXiv_CV
tags: arXiv_CV Knowledge Ontology Inference
author: Jianmin Ji, Fangfang Liu, Jia-Huai You
mathjax: true
---

* content
{:toc}

##### Abstract
Hybrid MKNF knowledge bases have been considered one of the dominant approaches to combining open world ontology languages with closed world rule-based languages. Currently, the only known inference methods are based on the approach of guess-and-verify, while most modern SAT/ASP solvers are built under the DPLL architecture. The central impediment here is that it is not clear what constitutes a constraint propagator, a key component employed in any DPLL-based solver. In this paper, we address this problem by formulating the notion of unfounded sets for nondisjunctive hybrid MKNF knowledge bases, based on which we propose and study two new well-founded operators. We show that by employing a well-founded operator as a constraint propagator, a sound and complete DPLL search engine can be readily defined. We compare our approach with the operator based on the alternating fixpoint construction by Knorr et al [2011] and show that, when applied to arbitrary partial partitions, the new well-founded operators not only propagate more truth values but also circumvent the non-converging behavior of the latter. In addition, we study the possibility of simplifying a given hybrid MKNF knowledge base by employing a well-founded operator, and show that, out of the two operators proposed in this paper, the weaker one can be applied for this purpose and the stronger one cannot. These observations are useful in implementing a grounder for hybrid MKNF knowledge bases, which can be applied before the computation of MKNF models. The paper is under consideration for acceptance in TPLP.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1707.01959](https://arxiv.org/abs/1707.01959)

##### PDF
[https://arxiv.org/pdf/1707.01959](https://arxiv.org/pdf/1707.01959)

