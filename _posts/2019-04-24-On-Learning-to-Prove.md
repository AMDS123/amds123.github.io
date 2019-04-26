---
layout: post
title: "On Learning to Prove"
date: 2019-04-24 23:54:59
categories: arXiv_AI
tags: arXiv_AI
author: Daniel Huang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we consider the problem of learning a (first-order) theorem prover where we use a representation of beliefs in mathematical claims instead of a proof system to search for proofs. The inspiration for doing so comes from the practices of human mathematicians where a proof system is typically used after the fact to justify a sequence of intuitive steps obtained by "plausible reasoning" rather than to discover them. 
 Towards this end, we introduce a probabilistic representation of beliefs in first-order statements based on first-order distributive normal forms (dnfs) devised by the philosopher Jaakko Hintikka. Notably, the representation supports Bayesian update and does not enforce that logically equivalent statements are assigned the same probability---otherwise, we would end up in a circular situation where we require a prover in order to assign beliefs. We then examine (1) conjecturing as (statistical) model selection and (2) an alternating-turn proving game amenable (in principle) to self-play training to learn a prover that is both complete in the limit and sound provided that players maintain "reasonable" beliefs. Dnfs have super-exponential space requirements so the ideas in this paper should be taken as conducting a thought experiment on "learning to prove". As a step towards making the ideas practical, we will comment on how abstractions can be used to control the space requirements at the cost of completeness.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.11099](http://arxiv.org/abs/1904.11099)

##### PDF
[http://arxiv.org/pdf/1904.11099](http://arxiv.org/pdf/1904.11099)

