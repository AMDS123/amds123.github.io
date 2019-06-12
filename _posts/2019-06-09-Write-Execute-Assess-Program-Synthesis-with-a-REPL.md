---
layout: post
title: "Write, Execute, Assess: Program Synthesis with a REPL"
date: 2019-06-09 23:12:40
categories: arXiv_AI
tags: arXiv_AI
author: Kevin Ellis, Maxwell Nye, Yewen Pu, Felix Sosa, Josh Tenenbaum, Armando Solar-Lezama
mathjax: true
---

* content
{:toc}

##### Abstract
We present a neural program synthesis approach integrating components which write, execute, and assess code to navigate the search space of possible programs. We equip the search process with an interpreter or a read-eval-print-loop (REPL), which immediately executes partially written programs, exposing their semantics. The REPL addresses a basic challenge of program synthesis: tiny changes in syntax can lead to huge changes in semantics. We train a pair of models, a policy that proposes the new piece of code to write, and a value function that assesses the prospects of the code written so-far. At test time we can combine these models with a Sequential Monte Carlo algorithm. We apply our approach to two domains: synthesizing text editing programs and inferring 2D and 3D graphics programs.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.04604](http://arxiv.org/abs/1906.04604)

##### PDF
[http://arxiv.org/pdf/1906.04604](http://arxiv.org/pdf/1906.04604)

