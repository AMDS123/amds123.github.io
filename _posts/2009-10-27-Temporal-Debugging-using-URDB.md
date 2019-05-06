---
layout: post
title: "Temporal Debugging using URDB"
date: 2009-10-27 17:31:02
categories: arXiv_CV
tags: arXiv_CV
author: Ana Maria Visan, Artem Polyakov, Praveen S. Solanki, Kapil Arya, Tyler Denniston, Gene Cooperman
mathjax: true
---

* content
{:toc}

##### Abstract
A new style of temporal debugging is proposed. The new URDB debugger can employ such techniques as temporal search for finding an underlying fault that is causing a bug. This improves on the standard iterative debugging style, which iteratively re-executes a program under debugger control in the search for the underlying fault. URDB acts as a meta-debugger, with current support for four widely used debuggers: gdb, MATLAB, python, and perl. Support for a new debugger can be added in a few hours. Among its points of novelty are: (i) the first reversible debuggers for MATLAB, python, and perl; (ii) support for today's multi-core architectures; (iii) reversible debugging of multi-process and distributed computations; and (iv) temporal search on changes in program expressions. URDB gains its reversibility and temporal abilities through the fast checkpoint-restart capability of DMTCP (Distributed MultiThreaded CheckPointing). The recently enhanced DMTCP also adds ptrace support, enabling one to freeze, migrate, and replicate debugging sessions.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/0910.5046](https://arxiv.org/abs/0910.5046)

##### PDF
[https://arxiv.org/pdf/0910.5046](https://arxiv.org/pdf/0910.5046)

