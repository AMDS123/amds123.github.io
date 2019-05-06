---
layout: post
title: "Polarities & Focussing: a journey from Realisability to Automated Reasoning"
date: 2014-12-21 13:25:11
categories: arXiv_CV
tags: arXiv_CV Face Relation
author: Stéphane Graham-Lengrand
mathjax: true
---

* content
{:toc}

##### Abstract
This dissertation explores the roles of polarities and focussing in various aspects of Computational Logic. These concepts play a key role in the the interpretation of proofs as programs, a.k.a. the Curry-Howard correspondence, in the context of classical logic. Arising from linear logic, they allow the construction of meaningful semantics for cut-elimination in classical logic, some of which relate to the Call-by-Name and Call-by-Value disciplines of functional programming. The first part of this dissertation provides an introduction to these interpretations, highlighting the roles of polarities and focussing. For instance: proofs of positive formulae provide structured data, while proofs of negative formulae consume such data; focussing allows the description of the interaction between the two kinds of proofs as pure pattern-matching. This idea is pushed further in the second part of this dissertation, and connected to realisability semantics, where the structured data is interpreted algebraically, and the consumption of such data is modelled with the use of an orthogonality relation. Most of this part has been proved in the Coq proof assistant. Polarities and focussing were also introduced with applications to logic programming in mind, where computation is proof-search. In the third part of this dissertation, we push this idea further by exploring the roles that these concepts can play in other applications of proof-search, such as theorem proving and more particularly automated reasoning. We use these concepts to describe the main algorithm of SAT-solvers and SMT-solvers: DPLL. We then describe the implementation of a proof-search engine called Psyche. Its architecture, based on the concept of focussing, offers a platform where smart techniques from automated reasoning (or a user interface) can safely and trustworthily be implemented via the use of an API.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1412.6781](https://arxiv.org/abs/1412.6781)

##### PDF
[https://arxiv.org/pdf/1412.6781](https://arxiv.org/pdf/1412.6781)

