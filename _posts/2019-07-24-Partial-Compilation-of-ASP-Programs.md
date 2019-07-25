---
layout: post
title: "Partial Compilation of ASP Programs"
date: 2019-07-24 14:42:57
categories: arXiv_AI
tags: arXiv_AI
author: Bernardo Cuteri, Carmine Dodaro, Francesco Ricca, Peter Sch&#xfc;ller
mathjax: true
---

* content
{:toc}

##### Abstract
Answer Set Programming (ASP) is a well-known declarative formalism in logic programming. Efficient implementations made it possible to apply ASP in many scenarios, ranging from deductive databases applications to the solution of hard combinatorial problems. State-of-the-art ASP systems are based on the traditional ground\&amp;solve approach and are general-purpose implementations, i.e., they are essentially built once for any kind of input program. In this paper, we propose an extended architecture for ASP systems, in which parts of the input program are compiled into an ad-hoc evaluation algorithm (i.e., we obtain a specific binary for a given program), and might not be subject to the grounding step. To this end, we identify a condition that allows the compilation of a sub-program, and present the related partial compilation technique. Importantly, we have implemented the new approach on top of a well-known ASP solver and conducted an experimental analysis on publicly-available benchmarks. Results show that our compilation-based approach improves on the state of the art in various scenarios, including cases in which the input program is stratified or the grounding blow-up makes the evaluation unpractical with traditional ASP systems.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.10469](http://arxiv.org/abs/1907.10469)

##### PDF
[http://arxiv.org/pdf/1907.10469](http://arxiv.org/pdf/1907.10469)

