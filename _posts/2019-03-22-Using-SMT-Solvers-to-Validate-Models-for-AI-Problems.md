---
layout: post
title: "Using SMT Solvers to Validate Models for AI Problems"
date: 2019-03-22 12:45:23
categories: arXiv_AI
tags: arXiv_AI
author: Andrei Arusoaie, Ionut Pistol
mathjax: true
---

* content
{:toc}

##### Abstract
Artificial Intelligence problems, ranging form planning/scheduling up to game control, include an essential crucial step: describing a model which accurately defines the problem's required data, requirements, allowed transitions and established goals. The ways in which a model can fail are numerous and often lead to a failure of search strategies to provide a quick, optimal, or even any solution. This paper proposes using SMT (Satisfiability Modulo Theories) solvers, such as Z3, to check the validity of a model. We propose two tests: checking whether a final(goal) state exists in the model's described problem space and checking whether the transitions described can provide a path from the identified initial states to any the goal states (meaning a solution has been found). The advantage of using an SMT solver for AI model checking is that they substitute actual search strategies and they work over an abstract representation of the model, that is, a set of logical formulas. Reasoning at an abstract level is not as expensive as exploring the entire solution space. SMT solvers use efficient decision procedures which provide proofs for the logical formulas corresponding to the AI model. A recent addition to Z3 allowed us to describe sequences of transitions as a recursive function, thus we can check if a solution can be found in the defined model.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.09475](http://arxiv.org/abs/1903.09475)

##### PDF
[http://arxiv.org/pdf/1903.09475](http://arxiv.org/pdf/1903.09475)

