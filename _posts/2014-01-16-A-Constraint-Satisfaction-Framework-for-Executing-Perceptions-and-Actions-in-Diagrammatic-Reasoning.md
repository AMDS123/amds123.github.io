---
layout: post
title: "A Constraint Satisfaction Framework for Executing Perceptions and Actions in Diagrammatic Reasoning"
date: 2014-01-16 05:00:46
categories: arXiv_CV
tags: arXiv_CV Inference Relation
author: Bonny Banerjee, B. Chandrasekaran
mathjax: true
---

* content
{:toc}

##### Abstract
Diagrammatic reasoning (DR) is pervasive in human problem solving as a powerful adjunct to symbolic reasoning based on language-like representations. The research reported in this paper is a contribution to building a general purpose DR system as an extension to a SOAR-like problem solving architecture. The work is in a framework in which DR is modeled as a process where subtasks are solved, as appropriate, either by inference from symbolic representations or by interaction with a diagram, i.e., perceiving specified information from a diagram or modifying/creating objects in a diagram in specified ways according to problem solving needs. The perceptions and actions in most DR systems built so far are hand-coded for the specific application, even when the rest of the system is built using the general architecture. The absence of a general framework for executing perceptions/actions poses as a major hindrance to using them opportunistically -- the essence of open-ended search in problem solving. Our goal is to develop a framework for executing a wide variety of specified perceptions and actions across tasks/domains without human intervention. We observe that the domain/task-specific visual perceptions/actions can be transformed into domain/task-independent spatial problems. We specify a spatial problem as a quantified constraint satisfaction problem in the real domain using an open-ended vocabulary of properties, relations and actions involving three kinds of diagrammatic objects -- points, curves, regions. Solving a spatial problem from this specification requires computing the equivalent simplified quantifier-free expression, the complexity of which is inherently doubly exponential. We represent objects as configuration of simple elements to facilitate decomposition of complex problems into simpler and similar subproblems. We show that, if the symbolic solution to a subproblem can be expressed concisely, quantifiers can be eliminated from spatial problems in low-order polynomial time using similar previously solved subproblems. This requires determining the similarity of two problems, the existence of a mapping between them computable in polynomial time, and designing a memory for storing previously solved problems so as to facilitate search. The efficacy of the idea is shown by time complexity analysis. We demonstrate the proposed approach by executing perceptions and actions involved in DR tasks in two army applications.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1401.3854](https://arxiv.org/abs/1401.3854)

##### PDF
[https://arxiv.org/pdf/1401.3854](https://arxiv.org/pdf/1401.3854)

